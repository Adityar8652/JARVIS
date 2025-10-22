# JARVIS - Just A Rather Very Intelligent System

A Python-based voice assistant that can execute commands, open applications, and answer questions using Google's Gemini AI.

## Features

✨ **Voice Commands** - Control your computer with natural speech
🎤 **Continuous Listening** - Always ready without restart delays
🤖 **AI-Powered** - Uses Google Gemini for intelligent responses
🚀 **Quick Actions** - Open apps, browsers, and system tools instantly

## Installation

1. Clone the repository:
```bash
git clone https://github.com/KrishnaSrinivas-24/JARVIS.git
cd JARVIS
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Set up your Google Gemini API key:
   - Get your API key from [Google AI Studio](https://makersuite.google.com/app/apikey)
   - Replace `"Paste your API Here"` in `jarvis.py` with your actual API key

## Usage

Run JARVIS:
```bash
python jarvis.py
```

### Available Commands

**Open Applications:**
- "Open Google" / "Open Edge" - Launch browsers
- "Open YouTube" / "Open Spotify" - Media platforms
- "Open Word" / "Open Excel" / "Open PowerPoint" - Office apps
- "Open Notepad" / "Open Calculator" - System utilities
- "Open GitHub" / "Open Discord" - Dev tools
- "Open Command Prompt" / "Open File Explorer" - System access

**Exit:**
- "Exit" - Close JARVIS

**General Questions:**
- Ask anything! If JARVIS doesn't recognize a command, it will use Gemini AI to answer your question.

## Recent Improvements

### Continuous Listening Optimization (Issue #1)
- ✅ Removed recursive restart after unknown responses
- ✅ Added proper error handling for all speech recognition exceptions
- ✅ Implemented timeout and phrase limits to prevent hanging
- ✅ Added ambient noise adjustment for better recognition
- ✅ Continuous loop without restart delays

**Benefits:**
- No more infinite loops on recognition errors
- Faster response time between commands
- Better error recovery
- Smoother user experience

## Requirements

- Python 3.7+
- Microphone access
- Internet connection (for speech recognition and Gemini AI)
- Windows OS (for application shortcuts)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the MIT License.
