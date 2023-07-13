# Hegazy SMTPs Checker

This script is a Python tool that allows you to check the validity and functionality of SMTP servers. It verifies the connection, authentication, and the ability to send an email using the provided SMTP server credentials.

## Project Information

- **Project:** Hegazy SMTPs Checker
- **Author:** Hegazy (@hegasy)

## Disclaimer

⚠️This code is intended for educational purposes only. Please use it responsibly and respect the legal and ethical guidelines regarding the usage of such tools.⚠️

## Prerequisites

Before running the script, ensure that you have the following dependencies installed:

- Python 3
- numpy
- alive-progress

You can install the required dependencies using the following command:

```shell
pip install numpy alive-progress
```

## Usage

1. Make sure the script has executable permissions. If not, you can set them using the following command:

   ```shell
   chmod +x script.py
   ```

2. Run the script using the following command:

   ```shell
   ./script.py
   ```

3. The script will prompt you for the necessary information:

   - List File: The path to a file containing a list of SMTP server credentials in the following format: HOST | PORT | USERNAME | PASSWORD.
   - Output File: The path to the output file where valid SMTP server credentials will be saved.
   - Send Test To Email: The email address where a test email will be sent to verify the SMTP server's functionality.
   - Connection Timeout (s): The timeout duration (in seconds) for establishing a connection to the SMTP server.

4. The script will start the process of checking the SMTP server credentials and display a progress bar.

5. Once the process is completed, the script will display the total number of credentials checked, the number of valid and invalid credentials, and the email address where you can check the deliverability of the valid results.
