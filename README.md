# CHAT-APPLICATION

**Company** : CODTECH IT SOLUTIONS

**Name** : SAITEJA MOTUKURI

**Intern ID** : CT08DUI

**Domain** : Full Stack Development

**Batch Duration** : December 25th, 2024 to January 25th, 2025

**Mentor Name** : Neela Santhosh Kumar

#  DESCRIPTION

1. Features:
Real-Time Messaging:

Users can send and receive messages instantly.
Messages are displayed in a chat window, distinguishing between the user's messages (aligned to the right) and messages from others (aligned to the left).
Username Customization:

Users can input their display name via a text field (defaults to "anonymous").
Typing Feedback:

When a user starts typing, a "User is typing..." message is broadcast to all clients.
Client Tracking:

Displays the total number of connected users dynamically at the bottom of the interface.
Timestamped Messages:

Messages include the sender's name and a timestamp (relative time like "a few seconds ago").
Notification Sound:

A notification sound plays when a new message is received.
2. Frontend Overview:
HTML Layout:

Title: "iChat"
Chat interface:
Name Input: Allows users to set their username.
Chat Area: Displays the list of messages (message-container).
Message Input & Send Button: Users can type and send messages.
CSS Styling:

Clean and modern design with a responsive layout.
Messages are styled with different background colors for the sender and recipient.
Uses Font Awesome icons for the user icon and send button.
Frontend Logic (JavaScript):

Handles message sending, receiving, typing feedback, and dynamically updating the DOM.
Integrates Moment.js for formatting timestamps.

3. How it Works:
Client Connects:
The app tracks the client and updates the total connected users.
Messaging:
A client sends a message, which is displayed in their UI and broadcast to others.
Typing Feedback:
When a user starts typing, feedback is shown to other clients.
Client Disconnects:
The app removes the client from the list and updates the total users.


#  OUTPUT







