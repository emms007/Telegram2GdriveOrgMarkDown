This nodejs script will:
- listen to a telegram bot in real time
- publish the content of the message sent to the telegram bot to a .org journal file on a gdive. It will create a new file for the day or will append to the existing one if existing). Lines are shown prefixed with a timestamp. "TODO" is supported and put as the first word if found within the message. 

The app must also be configured to support a google drive api account, see pre-req of https://developers.google.com/people/quickstart/nodejs for instance. 

Inspired from https://github.com/akhater/Lupin implementation that is more complete but focuses on Github for data sync.

