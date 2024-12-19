# virtual-assistant

# Virtual Assistant with Python

This project is a virtual assistant built with Python that can perform various tasks such as responding to voice commands, playing music, telling jokes or facts, searching Wikipedia, and opening websites. The assistant uses libraries like `pyttsx3` for text-to-speech, `speech_recognition` for speech input, and `pygame` for playing music.

## Features

1. **Voice Interaction**
   - The assistant listens to voice commands and responds using text-to-speech.

2. **Wikipedia Search**
   - It can fetch and read summaries from Wikipedia.

3. **Open Websites**
   - Opens popular websites like YouTube, Google, and Times of India.

4. **Tell the Time**
   - Responds with the current time.

5. **Play Music**
   - Plays a predefined music file from your system.

6. **Tell Jokes or Facts**
   - Shares random jokes or interesting facts.

7. **Graceful Exit**
   - Exits the program on command.

## Prerequisites

Make sure you have the following installed on your system:

1. **Python 3.6+**
2. **Required Python Libraries** (Install using `pip`):
    - `pyttsx3`
    - `speech_recognition`
    - `wikipedia`
    - `pygame`
    - `requests`

## Installation

1. Clone the repository or download the source code.
2. Install the required libraries using the following command:

```bash
pip install pyttsx3 SpeechRecognition wikipedia pygame requests
```

3. Ensure you have a music file saved at `C:/Users/kaman/Music/Gaaju bomma.mp3` or modify the path in the code to a music file available on your system.

## How to Run

1. Open the terminal or command prompt.
2. Navigate to the directory containing the script.
3. Run the script using:

```bash
python Data.py
```

## How It Works

1. The assistant starts by wishing the user based on the current time.
2. It listens to voice commands via the default microphone.
3. Based on the command, it performs one of the following actions:
   - Search Wikipedia and read a summary.
   - Open specific websites.
   - Tell the current time.
   - Tell a joke or fact.
   - Play a predefined music file.
   - Exit the program gracefully.

## Customization

- **Music Path**: Update the `music_path` variable in the `play_music` function to a valid path on your system.
- **Voice Settings**: Adjust the voice properties (e.g., speech rate, voice gender) using the `pyttsx3` library.
- **Jokes and Facts**: Add more jokes or facts to the `jokes_or_facts` list.

## Known Limitations

- Requires an active internet connection for Wikipedia searches.
- Speech recognition may not work well in noisy environments.
- The music file must exist at the specified path.

## Future Enhancements

- Add more commands for additional functionality.
- Integrate natural language processing (NLP) for better understanding of user commands.
- Allow dynamic music file selection.
- Add support for sending emails or managing tasks.

## License

This project is open-source and available for modification and personal use. Feel free to contribute or improve its functionality.

