


![Color Detection GIF](https://github.com/shreyamalogi/color-detector/blob/main/computer%20vision/Color%20detection/media/clrdetgif.gif)

# Color Detection App

Overwhelmed by the frustration of inconsistent color matching in design work?

Well, This Python project allows you to detect and identify colors from an image using the OpenCV library and a CSV file containing color names and RGB values.

### Features

- Detect and identify colors in images
- Interactive user interface
- Real-time color analysis

## Tech Stack

- **Programming Language:** Python
- **Libraries:** OpenCV, Pandas
- **CSV Data:** Color names and RGB values
- **User Interface:** Command-line and OpenCV GUI


## Prerequisites

Before you begin, ensure you have the following libraries installed:

```bash
pip install pandas opencv-python
```

## Usage

1. Clone the repository or download the project files.

2. Place the image you want to analyze in the project directory and specify its path in the `img_path` variable in the script.

3. Ensure you have a CSV file (`colors.csv`) with color names and their corresponding RGB values. The CSV file should have the following columns: 'color', 'color_name', 'hex', 'R', 'G', 'B'. If you don't have this file, you can create one or find a pre-existing dataset.

4. Update the `csv_path` variable in the script to point to your CSV file.

5. Run the script:

```bash
python color_detection.py
```

6. The image will be displayed in a window. Double-click on any area of the image to detect the color in that region. The name of the detected color and its RGB values will be displayed below the image.

7. Press the 'Esc' key to close the image window and exit the program.

## Example

You can use the provided `pic1.jpg` image for testing. The CSV file `colors.csv` contains a list of colors and their corresponding RGB values.

## Author

This project was created by Shreya Malogi

Please note that this is a basic color detection application, and you can expand it further or integrate it into other projects as needed.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

MIT License

Copyright (c) 2021 SHREYA MALOGI

## ⭐ Star and 🍴 Fork

If you find this project interesting or useful, we'd love for you to show your support by giving it a ⭐ star on GitHub. It's a simple gesture, but it means a lot to us!

And if you're feeling inspired or want to contribute, feel free to 🍴 fork this repository. You can use it as a starting point for your own projects or propose changes and improvements via pull requests. We welcome collaboration!

Let's make this project even better together! 🚀

