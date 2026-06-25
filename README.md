# Mini-chat_Python-OOP

A console-based Mini Chat System built in **Python** using **Object-Oriented Programming (OOP)**. I created this project to strengthen my understanding of OOP by building a simple chat application from scratch. The system allows users to join chatrooms, send messages, view chat history, and leave chatrooms while demonstrating how different objects work together in a real-world application.

---

## Features

* Create multiple users
* Create chatrooms
* Join and leave chatrooms
* Send and broadcast messages
* Maintain chat history
* Automatically assign a unique ID to every message
* Clean and modular object-oriented design

---

## OOP Concepts Used

This project helped me practice and understand the following OOP concepts:

* Classes and Objects
* Constructors (`__init__`)
* Encapsulation
* Composition (Chatroom manages Users and Messages)
* Class Variables
* Instance Variables
* Methods and Object Interaction

---

## Project Workflow

1. Create a chatroom.
2. Create one or more users.
3. Users join the chatroom.
4. Users send messages.
5. Each message is assigned a unique ID and stored in the chat history.
6. The chatroom displays the complete conversation history.
7. Users can leave the chatroom at any time.

---

## Classes

### `Message`

Represents a single chat message.

* Stores the sender
* Stores the message content
* Generates a unique message ID

### `User`

Represents a chatroom participant.

* Join a chatroom
* Leave a chatroom
* Send messages

### `Chatroom`

Manages the chat environment.

* Stores connected users
* Maintains chat history
* Broadcasts messages
* Displays all previous messages

---

## Technologies Used

* Python 3
* Object-Oriented Programming (OOP)

---

## Sample Output

```text
Hassan joined chatroom 'Python Lounge'
Safwan joined chatroom 'Python Lounge'

1: Hi (sent by Hassan)
2: Hello (sent by Safwan)

--- Chat History (Python Lounge) ---
1: Hi (sent by Hassan)
2: Hello (sent by Safwan)

Safwan left chatroom 'Python Lounge'
```

---

---

## Author

**Muhammad Hassan**

This project is part of my learning journey in Python and Object-Oriented Programming. I'm continuously building projects to improve my programming skills and apply new concepts as I learn them.
