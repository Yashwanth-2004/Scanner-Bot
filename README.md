# Scanner Bot

This is an OCR (Optical Character Recognition) scanner bot built using Python and the Pyrogram library. It allows users to send images of bills, extract data from them using OCR, and store the information in an Excel sheet.

## Features
- Extracts shop name, date, and amount from bill images.
- Creates an Excel sheet with the extracted data.
- Supports multiple bills scanning in a single session.

## Dependencies
- Python 3.x
- Pyrogram
- EasyOCR
- XlsxWriter

## Installation
1. Clone this repository to your local machine.
2. Install the dependencies by running:
3. Obtain API credentials from Telegram.
4. Replace `'api_id'`, `'api_hash'`, `'bot_token'`, and `'bot_username'` in the script with your actual credentials.

## Usage
1. Run the script using:
2. Start the bot by sending `/start` command in the chat.
3. Use `/help` command to get information about how to use the bot.
4. Send the number of bills you want to scan using the `/scan` command.
5. Send images of bills one by one when prompted.
6. Once all bills are scanned, the bot will generate an Excel sheet with the extracted data and send it to you.

## Support
For any issues or suggestions, please open an issue on [GitHub](https://github.com/your_username/ocr-scanner-bot).
