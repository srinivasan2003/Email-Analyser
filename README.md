# Email-Analyzer

## Overview

The Email Analyzer is a Python script designed to process and analyze email files in `.msg` and `.eml` formats. It extracts information and attachments from these files and organizes them into a structured format.

## Features

- **Supports Multiple Email Formats**: Handles both `.msg` (Microsoft Outlook) and `.eml` (standard email format) files.
- **Attachment Extraction**: Automatically extracts attachments from the email files and saves them to a designated directory.
- **Easy to Use**: Requires minimal setup and can be run from the command line.

## Prerequisites

- Python 3.x
- The following Python libraries are required:
  - `email`
  - `os`
  - `sys`
  - `re`
  - `colorama`
  - `extract_msg`

These can be installed via pip:

```bash
pip install colorama extract_msg
```

## Installation

1. Clone or download the repository to your local machine.
2. Ensure all the required libraries are installed.
3. Place your `.msg` or `.eml` files in the same directory as the script or provide the full path to the files when running the script.

## Usage

To run the script, open a terminal and navigate to the directory containing the script. Then, use the following command:

```bash
python email-analyzer.py <email_file>
```

Replace `<email_file>` with the path to your `.msg` or `.eml` file.

Example:

```bash
python email-analyzer.py example.msg
```

### Expected Output

- The script will create a directory named `Attachments` in the current working directory if it doesn't already exist.
- Attachments from the email file will be saved in the `Attachments` directory.
- The script will display the progress and any relevant messages in the terminal.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue to discuss potential changes.

## Contact

If you have any questions or need further assistance, please contact me via github.

---
