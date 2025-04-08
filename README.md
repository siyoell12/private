# PRIVATE CODING

This bot automates the process of creating accounts and using referral codes for the private.coding.

## Features

- Automatically generates random email addresses.
- Uses proxies to avoid IP bans.
- Logs the created accounts.
- Handles email verification.

## Requirements

- Node.js v18.20.5 LTS or latest.
- npm (Node Package Manager)

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/siyoell12/private.coding.git
   cd private
   ```

2. Install the dependencies:

   ```sh
   npm install
   ```

3. Create a `proxy.txt` file in the root directory and add your proxies (one per line).

4. change `config.json.example` to `config.json`

5. change your email, password (for get password you can see this video [Here](https://youtu.be/_rAoQeKpEtM?si=SLicWKn-AurwE8oa)), gemini apikey [Here](https://aistudio.google.com/app/apikey),

6. If you want using 2 Captcha service you can fill your apikey in `config.json` and change `"captha2Apikey": "your_2captcha_apikey",` with your apikey.

## Usage

1. Run the bot:

   ```sh
   npm start
   ```

2. Run 
   ```sh
   curl qrenco.de/
   ```

## Output

- The created accounts will be saved in `accounts.txt`.

## Notes

- Make sure to use valid proxies to avoid IP bans.
- The bot will attempt to verify the email up to 5 times before giving up.



