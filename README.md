# Auto Display Configuration

## Overview

The Display Refresh Rate Changer is a Windows program that automatically adjusts your display's refresh rate when you plug or unplug your charger. This smart feature allows you to optimize your power consumption and performance based on your power source, helping you get the best out of your display.

## Features

- Automatically switches display refresh rates when you plug or unplug your charger.
- Easy-to-use configuration options.
- Supports Windows.

## Getting Started

Follow these steps to get the program up and running on your Windows machine:

### Prerequisites

1. Download the `display.zip` file and extract its contents.
2. Move the `Qres` folder to your `C` drive.
3. In the `Qres` folder, you'll find two shortcut files: `60hz - shortcut` and `144hz - shortcut`. These shortcuts are responsible for changing your display settings.

### Configuration

By default, the program assumes a 1920x1080 display with a 144Hz refresh rate. If your display or refresh rate is different, you can customize the settings in the shortcut files:

1. Right-click on the shortcut file you want to customize and open it with Notepad.
2. Modify the line that looks like this: `qres x='your display width' y='your display height' f='your display supported refresh rate'`. Replace `'your display width'`, `'your display height'`, and `'your display supported refresh rate'` with your display's actual values.
3. you can remove and `f=144` and `f=60` part if you want to only change the resolution of display
4. Save the file and optionally rename it.
5. Don't forget to update the file path and name in the `display.pyw` file.

### Running the Program

1. Double-click the `display.pyw` file to execute the program.
2. The program will now automatically adjust your display's refresh rate based on your power source.

## Troubleshooting

If you encounter any issues or have questions, feel free to reach out for assistance.

## Contact

For any inquiries or support, you can contact Ketan Rathod at rketan588@gmail.com

