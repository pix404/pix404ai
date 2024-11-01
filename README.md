# PIX4AI

Generate batches of images in your browser with Stable Diffusion - private, free, and no installation required.

[Try it out](https://pix4.ai)

![PIX4AI Preview](img/pix4ai-social-share.png)

Please ensure you have a GPU with 8GB VRAM (or an M1/M2 Mac), and Chrome or Edge version 113 or higher.

PIX4AI is a modified version of [mlc-ai/web-stable-diffusion](https://github.com/mlc-ai/web-stable-diffusion) that comes with all the required files. You don't need to install Python, any pip dependencies, or execute build commands. I've eliminated all superfluous code, fixed critical bugs which made the original web-stable-diffusion project unusable, and added numerous quality-of-life features.

## Features

- 🖼️ Generate images in batches of unlimited size
- ⚡ Real-time diffusion preview (so cool!)
- 💾 Persist all of your generated images using IndexedDB
- 📲 Installable and usable offline as a PWA
- 📥 Download button available for saving files (utilizes prompt for the file name)
- 🌐 Entirely static files, making it easy to host for free

## Current Limitations

- All generated images are 512x512
- The only way to cancel generation is refreshing the page

## Usage

1. Open PIX4AI in your browser.
2. Ensure that you have a GPU with 8GB VRAM or an M1/M2 Mac.
3. Enter your desired input prompt in the "Prompt" text area. For example, you can enter "Art nouveau stained glass hummingbird".
4. Optionally, you can provide a negative prompt in [brackets].
5. Click on the "Generate" button to initiate the image generation process.
6. The generated images will be displayed in the output area on the right side of the screen.
7. You can download the generated images by clicking the "Download" buttons. The files will have the same name as the prompt.

## Contributing

We welcome contributions to improve PIX4AI. If you encounter any issues or have suggestions for new features, please feel free to open an issue or submit a pull request on the [GitHub repository](https://github.com/pix4ai/pix4ai/issues).

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).