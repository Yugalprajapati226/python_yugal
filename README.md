
## Overview

Powered by cutting-edge AI models running on [Replicate](https://replicate.com/about) and wrapped in a Streamlit interface, this app lets you transform plain text prompts into mesmerizing visual masterpieces.

## Technical Features

- **Neural Model**: Leverages the power of the replicate.run model for image generation, providing detailed and accurate depictions.
- **Streamlit Framework**: Built atop the versatile Streamlit library, ensuring a smooth and responsive UI/UX.
- **Dynamic Customization**: You can peek "under the hood", tune hyperparameters like guidance_scale, prompt_strength, and more for fine-grained control.
- **Gallery**: A curated gallery for inspiration, showcasing the prowess of the underlying model.

## Getting Started


1. Install the dependencies:

   ```python
   pip install -r requirements.txt
   ```

2. Rename the `.streamlit/example_secrets.toml` file to `.streamlit/secrets.toml`.

3. Paste your Replicate API token in the secrets.toml file:

   ```bash
   REPLICATE_API_TOKEN = "paste-your-replicate-api-token-here"
   ```

## Usage

1. Run the Streamlit app:

   ```python
   streamlit run streamlit_app.py
   ```

2. Navigate to the provided local URL, and voila! Start crafting your visual narratives.

## Contributions

Your insights can make this tool even better! Feel free to fork, make enhancements, and raise a PR.

## Attribution

- **Developed by**: The wizards over at [Stability AI](https://stability.ai/) 🧙‍♂️

- **Model type**: Diffusion-based text-to-image generative model


