# Stroker

# Keylogger Python Project

This Python project serves as a keylogger, capturing keystrokes, system information, clipboard content, screenshots, and audio recordings.

## Table of Contents

- [Libraries Used](#libraries-used)
- [Default Variables](#default-variables)
- [Usage](#usage)
- [Data Collection](#data-collection)
- [Encryption and Decryption](#encryption-and-decryption)
- [Additional Notes](#additional-notes)
- [Contributing](#contributing)
- [License](#license)

## Libraries Used

- `email.mime` for composing email messages
- `smtplib` for sending emails (optional)
- `pynput` for keyboard listening
- `sounddevice` for audio recording
- `PIL` for screenshots
- `cryptography` for data encryption

## Default Variables

- **Log Files:**
  - `key_log.txt`
  - `system_info.txt`
  - `clipboard.txt`
  - `audio.wav`
  - `screenshot.png`

- **Encrypted Log Files:**
  - `e_key_log.txt`
  - `e_system_info.txt`
  - `e_clipboard.txt`

- **Paths:**
  - `\KeyLogger_Info`
  - '\Cryptography_KeyLogger'

- **Email Configuration:**
  - `email_address`: Sender's email
  - `password`: Sender's email password
  - `toaddr`: Recipient's email

- **Recording Settings:**
  - `microphone_time`: Audio recording duration
  - `time_iteration`: Interval between data collection cycles
  - `number_of_iterations_end`: Number of data collection cycles

- **Encryption Key:**
  - `B0-wVqAFlgSQ4Y_KE_vss6fpPAA8TWMbH-_cjjYEvOE=`

## Usage

1. Clone the repository.

    ```bash
    git clone https://github.com/yourusername/keylogger-project.git
    ```

2. Install the required libraries.

    ```bash
    pip install -r requirements.txt
    ```

3. Edit variables in `main.py` for customization (email, recording settings, etc.).

4. Run the script.

    ```
    Advance Keylogger.ipynb file in Jupyter Notebook or convert to the IDE format you use and run.
    ```

## Data Collection

- Keystrokes: `key_log.txt`
- System Information: `system_info.txt`
- Clipboard Content: `clipboard.txt`
- Screenshots: `screenshot.png`
- Audio Recordings: `audio.wav`

## Encryption and Decryption

- Encrypted Files: `e_key_log.txt`, `e_system_info.txt`, `e_clipboard.txt`
- Encryption Key: Stored in `encryption_key.txt`

## Additional Notes

- This project is for educational purposes only. Use responsibly and ethically.
- Email sending requires a valid SMTP server and credentials.
- Adjust data collection settings according to your needs.
- Securely store the encryption key for decryption.

## Contributing

Contributions are welcome! Feel free to report bugs, suggest improvements, or add new features.

## License

This project is licensed under the MIT License.
