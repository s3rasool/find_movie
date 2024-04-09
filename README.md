# Bot README

## Bot Description
This Telegram bot is designed to search for IMDb information and movie posters using the OMDb API. It operates in inline mode, allowing users to search for movie details and posters directly within Telegram chats.

## Bot Functionality
### Searching for IMDb Information
Users can search for IMDb information about movies by sending messages in the format:

@bot_username <movie_title>

Upon receiving such a message, the bot will respond with a list of IMDb search results, including movie titles, years, and IMDb links.

### Searching for Movie Posters
Users can search for movie posters by sending messages in the format:

@bot_username <movie_title> only_poster

In this case, the bot will respond with movie posters directly.

## Setup Guide
1. **Obtaining OMDb API Key**: 
   - Obtain an API key from the OMDb website.

2. **Configuring the Bot**:
   - Set the `BOT_TOKEN` variable in `bot.py` to your Telegram bot token.
   
3. **Running the Bot**:
   - Run the bot using the provided Python script `bot.py`.

## Usage
Once the bot is up and running, users can interact with it directly within Telegram chats using the provided commands.

### Commands:
- `/start`: Start the bot and receive a greeting message.
- Inline Queries: Use inline queries to search for IMDb information and movie posters. The bot will respond accordingly.

## Dependencies
- Python 3.x
- `python-telegram-bot` library
- OMDb API
- Internet connection

## Additional Notes
- Ensure that your bot has been added to the desired Telegram chat and has the necessary permissions to send and receive messages.
- Handle errors and edge cases gracefully to provide a smooth user experience.