# EVE Voice Assistant

<p align="center">
  <img src=".github/eve-logo.png" alt="EVE Logo" width="300">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white" alt="C#">
  <img src="https://img.shields.io/badge/WPF-512BD4?style=for-the-badge&logo=.net&logoColor=white" alt="WPF">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/OpenAI%20API-412991?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI API">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
</p>

## About

EVE is a desktop application that combines speech recognition, natural language processing, and text-to-speech capabilities. This project was developed during a two-week college assignment by Juwan Jouma. The assistant can perform various tasks including weather updates, system controls, and natural conversations powered by OpenAI API.

## Features

- **Voice Recognition**: Responds to wake words like "Friday" and "Jarvis"
- **Natural Language Processing**: Understands and responds to user queries using OpenAI API
- **Weather Updates**: Provides real-time weather information based on user location
- **Multi-language Support**: Available in English, German, and Russian
- **User Authentication**: Secure login and registration system
- **Visual Feedback**: Dynamic animations indicating system state
- **Customizable Settings**: Personalize the assistant to your preferences

## Technologies

- **C#**: Core application development
- **WPF**: Windows Presentation Foundation for the user interface
- **Entity Framework**: ORM for database operations
- **Password Encryption (AES)**: For secure user authentication
- **MySQL**: Database for storing user information
- **OpenAI API**: Powers natural language understanding and generation
- **Picovoice**: Wake word detection
- **PyAudio**: Audio processing in Python
- **Python**: Backend processing for speech recognition
- **Silero TTS**: Text-to-speech synthesis
- **SpeechRecognition**: Converting speech to text
- **Weather API**: Real-time weather data

## Getting Started

### Prerequisites

- Windows operating system
- .NET 6.0 SDK or later
- Python 3.8 or later
- MySQL Server

### Installation

1. Clone the repository
2. Open the solution in Visual Studio
3. Restore NuGet packages
4. Required Python packages:
   The application will automatically install all required packages. If automatic installation fails, you can manually install them using:
   ```
   pip install -r req.txt
   ```
5. Configure your OpenAI API key in the application settings
6. Run the application

## See It In Action



## Project Structure

- **EVE**: Main WPF application
  - **AIBotInterface**: Main interface for the voice assistant
  - **Login/Registration**: User authentication system
  - **Weather**: Weather information integration
  - **Python Integration**: Bridge between C# and Python for speech processing

## Features in Detail

### Voice Recognition

EVE uses Picovoice for wake word detection, allowing the system to respond to custom wake words like "Friday" or "Jarvis". The SpeechRecognition library processes the audio input and converts it to text for further processing.

### Natural Language Processing

The application leverages OpenAI's powerful API to understand user queries and generate appropriate responses. This enables EVE to engage in natural conversations and provide helpful information.

### Weather Updates

EVE can provide real-time weather information including temperature, precipitation probability, cloud cover, and wind speed based on the user's location.

### Multi-language Support

The assistant supports multiple languages including English, German, and Russian.
## Contributors

<p align="center">
  <a href="https://github.com/The5TiM"><img src="https://img.shields.io/badge/The5TiM%20|%20Juwan%20Jouma-181717?style=for-the-badge&logo=github" alt="The5TiM | Juwan Jouma" /></a>
</p>