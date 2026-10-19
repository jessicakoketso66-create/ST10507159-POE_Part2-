# ST10507159-POE_Part2-
Sending Messages
# QuickChat – PROG5121 POE Part 2 (Sending Messages)

A console-based Java messaging application. Users log in, choose how many messages they want to enter, and then send, store or disregard each message. Messages are validated, given a unique ID and a message hash, and can be saved to a JSON file.

**Student name:Jessica Ralepelle
**Student number:ST10507159
**Module:** PROG5121

## Features

- Login required before any messages can be sent
- Welcome message: `Welcome to QuickChat.`
- Numeric menu:
  1. Send Messages
  2. Show recently sent messages (displays `Coming Soon.`)
  3. Quit
- The user sets how many messages they want to enter when the app starts, and can only enter that many
- The app keeps running until the user chooses **Quit**
- Each message has:
  - **Message ID**: randomly generated 10-digit number
  - **Message Hash**: first two digits of the ID, the message number, and the first and last words of the message, all in capitals (e.g. `00:0:HITONIGHT`)
  - **Recipient**: cell number with an international code
  - **Message**: no more than 250 characters
- After each message the user can choose to:
  - **Send**: `Message successfully sent.`
  - **Disregard**: `Press 0 to delete the message.`
  - **Store**: `Message successfully stored.` (saved to `messages.json`)
- Full details of each sent message are shown in this order: Message ID, Message Hash, Recipient, Message
- The total number of messages sent is shown when the user quits
