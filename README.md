[![keylogger](https://img.shields.io/badge/keylogger-blue?style=for-the-badge&logo=firefox&logoColor=white)]([https://shlokkokk.github.com/keylogger/](https://github.com/shlokkokk/keylogger))

## Overview
- This project is a basic keylogger written in Python that captures keystrokes and sends them to a specified email address at custom intervals. 
- Special keys like Ctrl, Shift, Enter, Backspace, Caps Lock, etc., are formatted as 
`* pressed_{key} *`.

## Features
- Captures all keystrokes, including special keys.
- Sends captured keystrokes to an email address at specified intervals.
- Easy to configure and deploy.

## Requirements
- Python 3.x
- `pynput` library

## Installation

### Clone the Repository
1. Open your terminal or command prompt.
   
2. Clone the repository using the following command:
   ```bash
   git clone https://github.com/shlokkokk/keylogger.git
   cd keylogger
   
3. Set Up a Virtual Environment
 - On Windows
    ```bash
    python -m venv keylogger_env
    keylogger_env\Scripts\activate
    
  - ON macOS/Linux
    ```bash
    python3 -m venv keylogger_env
    source keylogger_env/bin/activate
    
4. Install Required Packages
   - Install the necessary Python package
   ```bash
    pip install pynput


Configuration
-------------

Open keylogger.py and configure the following variables:

*   EMAIL\_ADDRESS: Your email address.
    
*   EMAIL\_PASSWORD: Your email password.
    
*   RECIPIENT\_EMAIL: The email address where keystrokes will be sent.
    
*   INTERVAL: Time interval in seconds to send keystrokes.
    

Usage
-----

- Ensure your virtual environment is activated.
  ```bash  
      python keylogger.py
    

Contributing
------------

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
