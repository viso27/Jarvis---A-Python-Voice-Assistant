# Jarvis---A-Python-Voice-Assistant
Jarvis is a voice-activated Python assistant that can perform various tasks such as answering queries, opening websites, sending emails, playing music, telling the time, and more. This project utilizes speech recognition, text-to-speech, and various Python libraries to create an interactive voice assistant.


## Features

-Speech Recognition: Converts your speech into text using the Google Web Speech API.

-Text-to-Speech: Uses the pyttsx3 library to speak back responses.

-Wikipedia Search: Performs searches on Wikipedia and reads out the summary.

-Open Websites: Opens websites like YouTube, Google, and StackOverflow in the browser.

-Play Music: Plays music from a specified directory on your computer.

-Tells Time: Announces the current time.

-Send Email: Sends emails via Gmail using SMTP.



## Required Libraries:

To run this project, make sure you have Python installed along with the following libraries:

-Use Python3.9 for better compatibility

-pyttsx3 - For converting text to speech.

-speechrecognition - For recognizing speech from the microphone.

-wikipedia - To fetch Wikipedia summaries.

-webbrowser - For opening websites.

-os - For interacting with the operating system.

-smtplib - For sending emails.

You can install the required libraries using the following commands:

```bash
pip install pyaudio
pip install pyttsx3
pip install SpeechRecognition
pip install wikipedia
```




## Run Locally

Clone the project

```bash
git clone https://github.com/viso27/Jarvis---A-Python-Voice-Assistant.git


```

Go to the project directory

```bash
cd Jarvis---A-Python-Voice-Assistant
```

Run the script

```bash
python jarvis.py

```


## Commands

Here are a few commands you can use with Jarvis:

-Wikipedia Search: "Wikipedia [your query]"

Example: "Wikipedia Python programming"

-Open Websites: "Open [website name]"

Example: "Open YouTube", "Open Google"

-Play Music: "Play music"

This will play the first song in the specified music directory (D:\Music).

-Time: "What is the time?"

The assistant will respond with the current time.

-Open Code Editor: "Open code"

You can specify the path of your code editor in the script (e.g., Visual Studio Code).

-Send Email: "Email to [name]"

The assistant will ask what to say in the email and will send it via the configured Gmail account.


## Customization

-Music Directory: You can change the directory from which music will be played by modifying the path in the music_dir variable.

```bash
music_dir = 'D:\\Music'
```

-Code Editor: Update the path to your code editor (e.g., Visual Studio Code) in the script.

```bash
codePath = "C:\\Users\\ \\AppData\\Local\\Programs\\Microsoft VS Code\\Code.exe "
```

-Gmail Settings: You need to input your Gmail credentials (email and password) to send emails. Be cautious about keeping your credentials secure.

```bash
server.login('youremail@gmail.com', 'yourpassword')
```






