# xss_scan
## About the Tool ⚒️

`xss_scan` is a simple Python script designed for finding CVE-2023-29489 vulnerability in cpanel.

## Features ⚙️

- **CVE-2023-29489 Scanning:** Identifies and scans for the CVE-2023-29489 vulnerability.
- **URL Input:** Supports scanning a single URL or reading multiple URLs from a file.
- **Output Logging:** Allows users to write the scan results to an output file.
- **Telegram Notification:** Option to create Telegram notifications for scan results.

## Prerequisites 🧩

Before using `xss_scan`, make sure you have the following prerequisites installed:

1. **Python 3.x**: Ensure you have Python 3.x installed on your system.

   - [Download Python](https://www.python.org/downloads/)

2. **Required Python Packages**:

   - **Click**: Install the `click` library using the following command:

     ```bash
     pip install click
     ```

   - **Requests**: Install the `requests` library using the following command:

     ```bash
     pip install requests
     ```

   - **PyYAML**: Install the `PyYAML` library using the following command:

     ```bash
     pip install PyYAML
     ```

3. **Telegram Notification (Optional)**:

   If you plan to use the Telegram notification feature, you'll need to set up a Telegram bot and obtain your chat ID. Follow these steps:

   - Create a Telegram bot using the [BotFather](https://core.telegram.org/bots#botfather).
   - Obtain your chat ID using the [get_id_bot](https://t.me/get_id_bot).


## PyPi Module Link🔗
[Click Here](https://pypi.org/project/xss-scan/1.0.1/)

## Installation ⬇️
```bash
pip install xss-scan=1.0.1
```


## Usage 

```bash
CVE-2023-29489 -u https://example.com
CVE-2023-29489 -i urls.txt -o results.txt
CVE-2023-29489 -u https://example.com -c your_telegram_chat_id
```

## Disclaimer 
This script is intended for educational and ethical purposes only. Unauthorized use of this script to perform malicious activities is strictly prohibited. The developers are not responsible for any misuse or damage caused by this script.

## Version History 
`v1.0`: Find CVE-2023-29489 in cpanel

## License 🪪
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)

## Author 👤
[@m0hamedsha0aib](https://github.com/m0hamedsh0aib)
 
