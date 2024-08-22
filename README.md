# Pixel Art Generator

This project is a Hugging Face Space that generates pixel art from any prompt using Gradio. The model used for image generation is `stabilityai/sdxl-turbo`.

## Demo

You can try out the demo [here](https://huggingface.co/spaces/pranayyy/pixel_art).

## Features

- Generate pixel art from any text prompt
- Easy-to-use interface powered by Gradio
- High-quality image generation using the `stabilityai/sdxl-turbo` model

## Setup

To run this project locally, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/Sanjit1806/pixel-art.git
    cd pixel-art
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the Gradio app:

    ```bash
    python app.py
    ```

4. Open your browser and go to `http://localhost:7860` to access the app.

## Usage

Enter any text prompt in the input box, and the model will generate a corresponding pixel art image. 

## Model

The image generation is powered by the `stabilityai/sdxl-turbo` model from Hugging Face. You can find more details about the model [here](https://huggingface.co/stabilityai/sdxl-turbo).

## Dependencies

- Gradio
- Hugging Face Diffusers
- Other dependencies are mentioned in the `requirements.txt` file

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes or additions.


## Acknowledgements

- [Hugging Face](https://huggingface.co/) for providing the model and platform
- [Gradio](https://gradio.app/) for the user interface framework

## Contributors
- [github.com/pran-ayyy](https://github.com/pran-ayyy)
- [github.com/Sanjit1806](https://github.com/Sanjit1806)
