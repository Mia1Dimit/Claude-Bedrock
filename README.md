# Claude-Bedrock Notebooks

This repository contains a set of Jupyter notebooks demonstrating how to interact with Amazon Bedrock's Claude models using the `boto3` Python SDK. Each notebook explores a different aspect of the API, including basic requests, system messages, streaming, and output control.

## Contents

- **001_Api_Requests.ipynb / 001_Api_Requests_complete.ipynb**: Basic API requests to Claude via Bedrock.
- **002_System_Messages.ipynb / 002_System_Messages_complete.ipynb**: Using system messages to control model behavior.
- **003_Streaming.ipynb / 003_Streaming_complete.ipynb**: Handling streaming responses from the API.
- **004_Controlling_Output.ipynb / 004_Controlling_Output_complete.ipynb**: Techniques for controlling and formatting model output.

Each pair of files includes an exercise notebook and a completed solution.

## Usage

1. **Install dependencies**: These notebooks require Python 3.8+ and the `boto3` library. Install with:
   ```bash
   pip install boto3
   ```
2. **Configure AWS credentials**: You must have valid AWS credentials with access to Bedrock. Credentials are **not** included in this repository and should be configured using the AWS CLI or environment variables. See [AWS documentation](https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-quickstart.html) for setup instructions.
3. **Run notebooks**: Open any notebook in Jupyter or VS Code and execute the cells.

## Security & Credentials

- All authentication is handled via local AWS configuration (e.g., `~/.aws/credentials` or environment variables).
- The `.gitignore` file excludes `.venv/` and all `.txt` files by default.

## License

This project is for educational purposes. See individual notebooks for additional licensing or usage notes.
