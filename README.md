For a completely rebuilt and more efficient Telegram markov bot with more features, see: https://gitlab.com/mikesbytes/telegram-markov-bot

# Markov_Chatbot

This is a fork of 39bit's Markov_Bot program, however this has been modified to have a 1/30th chance to send a markov message every time another user in the chat sends a message. There is a 1-4 second randomized delay before Markov sends a message in this fashion, making him function as a pseudo-chatbot meant for groupchats.

Requires at least Python 3.3. By default, only sh-compatible shells and Unix-based systems are supported. espeak and opusenc are required for TTS: see the generateMarkovOgg function.

Used libraries: requests (https://pypi.python.org/pypi/requests)
