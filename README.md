# Key Logger Algorithm

Welcome to the Key Logger Algorithm project! This repository contains a Python implementation for logging keystrokes using the pynput library. Please note that key logging should only be used responsibly and ethically.

## Overview

This project demonstrates a basic key logging algorithm that records keystrokes from the user's keyboard using the pynput library in Python. It captures characters, spaces, new lines, and can save the logged data to a text file upon pressing the Escape key.

## Algorithm Details

### Logging Keystrokes

The `on_press` function listens for keyboard events using the pynput library:
- It captures characters typed by the user and appends them to `logged_keys`.
- Special keys like space, enter, and escape are handled to format the logged text appropriately.
- Pressing the Escape key terminates the logging process and saves the logged keystrokes to a file named 'keylog.txt'.

### Ethical Use

**Important**: This key logger is provided for educational purposes and should only be used with explicit consent from the owner of the computer or device being monitored. Unauthorized use or distribution of key logging software may violate privacy laws and ethical standards.

## Usage

To use this program:
1. Run the `key_logger.py` script.
2. The program will start logging keystrokes in the background.
3. To stop logging, press the Escape key.
4. The logged keystrokes will be saved to 'keylog.txt' in the same directory.

## Example

```plaintext
Here is an example of the logged keystrokes:

Hello world!
This is a test.
```
## Contributing
Contributions that improve functionality, enhance security measures, or provide clearer documentation are welcome. Fork this repository, make your changes, and submit a pull request. For major changes, please open an issue to discuss the proposed modifications.

Always prioritize ethical considerations when using this key logging algorithm. 🔐⌨️
