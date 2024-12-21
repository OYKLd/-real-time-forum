# Upgraded Forum Project

## Project Objectives

This project aims to create an enhanced forum with the following features:

- Registration and Login
- Creation of posts
- Commenting on posts
- Private Messaging
- Real-time interactions using WebSockets

## Features

### 1. Registration and Login
- Users can register by providing:
  - Nickname
  - Age
  - Gender
  - First Name
  - Last Name
  - Email
  - Password
- Users can log in using either their nickname or email combined with the password.
- A logout option is available from any page.

### 2. Posts and Comments
- Users can create posts categorized like in the previous forum.
- Users can comment on posts.
- Posts are displayed in a feed format.
- Comments are visible only when users click on a post.

### 3. Private Messages
- A chat feature allows users to send private messages.
- Online/offline user status is displayed, organized by the last message sent.
- Users can send messages to those who are online.
- Clicking on a user reloads past messages, displaying the last 10 messages with the option to scroll for more.
- Messages include:
  - Date of sending
  - User name of the sender
- Real-time message notifications using WebSockets.
## Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Golang
- **Database**: SQLite

## Project Structure
REAL-TIME-FORUM/
├── chat/
│ ├── client.go
│ ├── message.go
│ └── room.go
├── functions/
│ ├── api.go
│ ├── database.go
│ ├── database_test.go
│ ├── helper.go
│ └── structs.go
├── static/
│ ├── js/
│ └── styles.css
├── templates/
│ └── index.html
├── main.go
├── go.mod
├── go.sum
└── README.md
