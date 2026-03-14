# CHITTI Voice Assistant

A personal voice assistant built with Python that can perform various tasks through voice commands.

## Features

- **Voice Recognition**: Listens to your commands using Google Speech Recognition
- **Text-to-Speech**: Responds with a female voice using pyttsx3
- **Play Music**: Play songs on YouTube
- **Time Telling**: Get current time
- **Wikipedia Search**: Get information about people and topics
- **Jokes**: Tell random jokes
- **Application Control**: Open Chrome and VS Code
- **Custom Responses**: Special responses for specific queries

## Requirements

- Python 3.6+
- Microphone for voice input
- Internet connection for speech recognition and YouTube playback
- Windows OS (currently configured for Windows paths)

## Dependencies

- speech_recognition
- pyttsx3
- pywhatkit
- wikipedia
- pyjokes

## Installation

1. Clone or download this repository
2. Install the required dependencies:
   ```bash
   pip install speech_recognition pyttsx3 pywhatkit wikipedia pyjokes
   ```

## Usage

Run the assistant:
```bash
python assistant.py
```

The assistant will greet you and start listening for commands. Speak clearly into your microphone.

## Available Commands

- **"play [song name]"** - Plays the song on YouTube
- **"what's the time"** - Tells the current time
- **"who is [person name]"** - Provides Wikipedia summary of the person
- **"who is neeru"** - Special response about the owner
- **"joke"** - Tells a random joke
- **"open chrome"** - Opens Google Chrome browser
- **"open code"** or **"open vs code"** - Opens Visual Studio Code
- **"exit"** or **"stop"** - Stops the assistant

## How It Works

1. The assistant uses `speech_recognition` to listen for voice commands
2. Commands are processed using Google Speech Recognition API
3. Responses are generated using text-to-speech with a female voice
4. Various libraries handle specific functionalities like YouTube playback, Wikipedia searches, etc.

## Troubleshooting

- **Microphone Issues**: Ensure your microphone is properly connected and not muted
- **Network Issues**: Some features require internet connection
- **Chrome Path**: The Chrome path is hardcoded for Windows; modify if needed
- **Voice Recognition Errors**: Speak clearly and ensure good microphone quality

## Contributing

Feel free to fork this project and add more features or improve existing functionality.

## License

This project is open source and available under the MIT License.
