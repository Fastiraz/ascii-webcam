<div align="center">
  <h1>
    <code>
      ASCII Webcam
    </code>
  </h1>
  <p>
    This is a Python script that captures webcam video and converts it into ASCII
    art in real-time. You can use it to create fun and creative visual effects
    using your webcam.
  </p>
</div>

---

## Prerequisites

Before running this script, make sure you have the following dependencies installed:

- OpenCV: OpenCV is used for capturing webcam frames.
- numpy: Numpy is used for numerical operations.
- pynput: Pynput is used for handling keyboard input.

You can install these dependencies using:

```bash
python3 -m pip install opencv-python numpy pynput
```

## Usage

1. Clone this repository to your local machine or download the script.
2. Open a terminal and navigate to the directory where the script is located.
3. Run the script:

```bash
python3 ascii_webcam.py
```

The webcam feed will start, and you will see the live video stream converted
into ASCII art in your terminal.
To exit the program, press the `ESC` key.

## Customize

You can customize the script by modifying the following parameters:

- `cols` and `rows`: Adjust these values to change the dimensions of the ASCII art output. Smaller values will result in more detail, while larger values will produce a coarser image.

- `CHAR_LIST `: You can replace the character list to use different characters for the ASCII art. The default list consists of `' .'`, which represents darker and lighter areas of the image, but you can replace it with characters that suit your preference.

## Compatibility

This script is compatible with Windows, Linux, and macOS operating systems.
It automatically detects your OS and uses the appropriate webcam capture method.


## Credits

Thanks to [Micode](https://github.com/michael-dm) for the script base.
This version is improved.
The image is centered by default and can be customized.
Instead of displaying a new frame with a new `print`, the old one is replaced by the new one.
