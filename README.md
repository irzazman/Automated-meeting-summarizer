<<<<<<< HEAD
# Google Meet Bot

A simple Selenium-based bot to automate joining Google Meet meetings.

## Features

- Logs in to a Google account
- Enters a display name
- Turns off microphone and camera before joining
- Joins a specified Google Meet link

## Setup

1. **Clone the repository:**
   ```sh
   git clone https://github.com/irzazman/Automated-meeting-summarizer.git
   cd google_bot
   ```

2. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

3. **Configure environment variables:**
   - Copy `.env.example` to `.env`:
     ```sh
     cp .env.example .env
     ```
   - Edit `.env` and fill in your Google credentials and meeting link.

4. **Run the bot:**
   ```sh
   python google_meet_bot.py
   ```

## Notes

- **Never share your `.env` file or credentials.**
- This bot uses Selenium and requires [ChromeDriver](https://chromedriver.chromium.org/downloads) installed and available in your PATH.
- For educational and personal use only.

## Demo

![Demo](demo.gif)

