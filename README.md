# Markov_Bot

This is a clone of 39bit's Markov_Bot program, however this has been modified to randomly respond without a /markov command 1 out of every 30 messages sent in a telegram chat.

Generates messages in chats based on Markov chains.

Requires at least Python 3.3.

By default, only sh-compatible shells and Unix-based systems are supported. espeak and opusenc are required for TTS: see the generateMarkovOgg function.

Used libraries: requests (https://pypi.python.org/pypi/requests)
