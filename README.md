# X11 Color Paint App Documentation

## Overview
This is a simple color paint application created using X11. It allows users to draw on a canvas using various colors and save their drawings.

## Features
- Drawing: Users can draw on the canvas using a mouse or touchpad.
- Color Selection: Users can select from a variety of colors to draw with.
- Saving: Users can save their drawings to a file for later viewing or editing.
- Clearing: Users can clear the canvas to start a new drawing.
- **Update:** Utilizes [SDL (Simple DirectMedia Layer)](https://www.libsdl.org/) and [SDL_ttf](https://www.libsdl.org/projects/SDL_ttf/) for improved graphics and text rendering capabilities.

## Installation
To use the X11 Color Paint App, follow these steps:
1. Clone the repository from GitHub: `git clone https://github.com/yourusername/x11-color-paint-app.git`
2. Navigate to the project directory: `cd x11-color-paint-app`
3. Compile the source code: `gcc -o paint main.c -lX11`
4. Run the executable: `./paint`

If you're already in your project directory, you can simply use these commands:

```bash
cd ~/paintcoloured
make
./paint
```
## Usage

- Upon running the application, a window will open displaying a canvas.
- Use the mouse or touchpad to draw on the canvas.
- To select a color, use the color palette provided.
- To save your drawing, click on the "Save" button and specify the file name.
- To clear the canvas, click on the "Clear" button.

## Dependencies

This project requires the X11 library. Ensure that you have the X11 development libraries installed on your system before compiling the source code. Additionally, the project utilizes [SDL (Simple DirectMedia Layer)](https://www.libsdl.org/) and [SDL_ttf](https://www.libsdl.org/projects/SDL_ttf/) for enhanced graphics and text rendering capabilities.

## Contributing

Contributions are welcome! If you'd like to contribute to the project, please follow these steps:

1. Fork the repository on GitHub.
2. Create a new branch with your feature or bug fix: `git checkout -b feature-or-fix`.
3. Commit your changes: `git commit -am 'Add new feature'`.
4. Push to the branch: `git push origin feature-or-fix`.
5. Submit a pull request on GitHub.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Author
This color paint application was developed by [George Goldman](https://github.com/georgegoldman).

