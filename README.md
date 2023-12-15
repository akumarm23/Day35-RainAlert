# Weather Alert Python v0.1

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python Version](https://img.shields.io/badge/python-3.9-teal.svg)](https://www.python.org/downloads/release/python-390/)
![Version](https://img.shields.io/badge/version-v0.1-navy)

## Description

The Weather Alert Python (`main.py`) is a script that checks the upcoming weather forecast using the OpenWeatherMap API and sends an alert via Twilio if rain is predicted. It provides a simple way to stay informed about potential rain.

## Setup

To run and test the code, you need to update the following places:

1. Replace `__YOUR_OWM_API_KEY__` with your OpenWeatherMap API key.
2. Replace `__YOUR_TWILIO_ACCOUNT_ID__` with your Twilio account ID.
3. Replace `__YOUR_TWILIO_AUTH_TOKEN__` with your Twilio authentication token.
4. Replace "YOUR TWILIO VIRTUAL NUMBER" with your Twilio virtual number.
5. Replace "YOUR TWILIO VERIFIED REAL NUMBER" with your Twilio verified real number.

## Requirements

- Python 3.9
- `requests` library (install with `pip install requests`)
- `twilio` library (install with `pip install twilio`)

## How it Works

1. The script queries the OpenWeatherMap API to get the upcoming weather forecast.
2. It checks if rain is predicted in the next few hours.
3. If rain is predicted, it sends an alert via Twilio.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/akumarm23/Day35-RainAlert.git
   cd Day35-RainAlert
   ```

2. Update the necessary details in the script.

3. Run the script:

   ```bash
   python main.py
   ```

4. Check your Twilio messages for rain alerts.

## Acknowledgments

Feel free to contribute and enhance the functionality of this Weather Alert Python script! Stay dry!
