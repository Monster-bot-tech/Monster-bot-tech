- 👋 Hi, I’m @Monster-bot-tech
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Monster-bot-tech/Monster-bot-tech is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
#!/bin/bash

# Ensure aircrack-ng is installed
if ! command -v aircrack-ng &> /dev/null
then
    echo "aircrack-ng could not be found, please install it first."
    exit
fi

# Capture file and wordlist
CAPTURE_FILE="capture.cap"
WORDLIST="/path/to/wordlist.txt"

# Check if capture file exists
if [ ! -f "$CAPTURE_FILE" ]; then
    echo "Capture file not found: $CAPTURE_FILE"
    exit
fi

# Check if wordlist file exists
if [ ! -f "$WORDLIST" ]; then
    echo "Wordlist not found: $WORDLIST"
    exit
fi

# Run aircrack-ng with

