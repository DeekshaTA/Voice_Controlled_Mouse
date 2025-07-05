# Voice-Controlled Mouse

This project allows you to control your computer mouse using voice commands such as "move up", "move down", "left click", "right click", and more. It is built using Python and uses speech recognition to convert your spoken commands into mouse movements and actions.

To run this project, make sure you have Python 3.7 or above installed. Then, install the required libraries by running:

```bash
pip install SpeechRecognition pyaudio pyautogui
```

After installing the dependencies, open the terminal in the project folder and run the script using:

```bash
python app.py
```

The program will access your microphone and wait for voice commands. Based on your input, the mouse will move or click accordingly.

The main files in this project include:
- `app.py` – handles voice input and mouse control
- `Proton.py` – may contain helper logic
- `web/` – contains frontend files like `index.html`, `css`, `js`, and `images`

Project folder structure:

```
VOICE-CONTROLLED_MOUSE/
├── app.py
├── Proton.py
├── web/
│   ├── index.html
│   ├── css/
│   ├── js/
│   └── images/
└── README.md
```
