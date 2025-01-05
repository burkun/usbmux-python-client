# usbmux-python-client
python client of https://cgit.sukimashita.com/usbmuxd.git

# Introduction

update for python3

# Prerequisite

- An iMac, Mac mini or Macbook.
- Google Chrome installed

# Installation

If you are using Mac

Run the following command in your terminal
```bash
curl "https://raw.githubusercontent.com/huangjimmy/usbmux-python-client/master/usbdebug.py" -o /usr/local/bin/usbdebug.py 
chmod +x /usr/local/bin/usbdebug.py
```

# Usage
- Launch your app compiled with debugger
- Connect your iPhone/iPad to your Mac with USB
- Know the debugger port of your phone, say 56123
- run the following command in your terminal
```bash
usbdebug.py 56123
```
- Wait a few seconds and then Chrome will open the debugger url for you.
