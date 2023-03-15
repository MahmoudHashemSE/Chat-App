# Chat App

Chat App is a real-time chat application built using Django and WebSockets. It allows users to create accounts, join chat rooms, and chat in real-time with other users in the same room.

## Features

- User authentication: users can create accounts and login
- Chat rooms: users can create chat rooms or join existing ones
- Real-time chat: messages are sent and received in real-time using WebSockets
- Room history: users can view the previous messages in a chat room
- User profiles: users can edit their profiles and upload profile pictures

## Installation

1. Clone the repository:

```bash
git clone https://github.com/MahmoudHashemSE/Chat-App.git
```

```bash
cd chat-app
```

2. Install requirements

```bash
poetry install
```

3. Create a MySQL database
```sql
CREATE DATABASE chat CHARACTER SET utf8;
```

4. Start Redis Server
```bash
redis-server
```

5. Init database
```bash
poetry run py manage.py migrate
```

6. Create admin user
```bash
poetry run py manage.py createsuperuser
```

7. Run development server
```bash
poetry run py manage.py runserver
```

## Usage

1. Create an account or login if you already have one.
2. Create a chat room or join an existing one.
3. Start chatting in real-time with other users in the same room.

## Technologies used

- Django
- Django Channels
- Django Rest Framework
- JavaScript
- HTML
- CSS