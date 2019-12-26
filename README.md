# AutoBot: a home automation system that communicates via Telegram

The goal of this system is to create a unified system of automation and organization between many roommates.

##### The system consists of three main sub-projects tat will be elaborated on later:
- the Telegram bot
- the Smart Board
- the Door Entry system
- Backend server that manages all the data/messages/logging

## System Rundown

##### The following are a few user stories that outline the operation of this system:
- A guest rings the doorbell. The group chat receives a message from AutoBot notifying all members of a guest. The notification message will have an attached button that would say "I'll get it" that would tell the other members that they don't need to get up and check.
- A roommate has a guest coming over in a few days. The roommate sends a private message to AutoBot to add a new item to the roommate calendar. The bot updates the Google Calendar immediately which in turn updates the live calendar on the smart board.
- A roommate arrives late at night and uses either a keycard or the NFC on their phone to enter the house. The door unlocks and logs the entry to the log to check later but doesn't display it anywhere. Every week, it generates a report and emails it to the group, analytics on user entries/exits.
- A roommate wants to send a message to a specific other roommate anonymously akin to a post-it note. They send a private message to AutoBot and tells it that this is an anonymous message. When the user approaches the smart board, it would recognize the specific user and show them their post-its along with the other information.
- A roommate wants to check the roommate schedule or their post-its from their room or when they're away from the house, they send a private message to AutoBot who generates a report for them.

### Telegram Bot
I don't know how this would be created or run, but there are enough resources online to figure it out. I know this will be operated with buttons instead of text entries.

### Smart Board
This could be using DAKboard as the base, but I will want to allow for multiple users and facial recognition for the post-its system and future features.

### Door Entry
An NFC keycard based system that auto-locks, logs entries and exits, reminds group chat that door isn't closed, and has a smart doorbell notification/logging system. Possibly with a camera.

### Server
This would coordinate all the moving parts, allow for creation of logs, databases, and 0 downtime.

## Required components

### Telegram Bot
- [ ] ???

### Smart Board
- [ ] Raspberry pi
- [ ] Old monitor
- [ ] Webcam
- [ ] Frame for display
- [ ] ???

### Door Entry
- [ ] Raspberry pi
- [ ] NFC Reader
- [ ] NFC Writer
- [ ] Key cards or fobs
- [ ] Webcam
- [ ] Vandal button for doorbell
- [ ] Smart lock
- [ ] Servo
- [ ] ???

### Server
- [ ] ???


## Final Notes
 Much of this is unknown territory for me so all of this is subject to change in scope and content