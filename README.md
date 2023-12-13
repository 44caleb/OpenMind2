# OpenMind2
A chatroom application for ALX porfolio project

## Introduction
OpenMind at its core is a chatroom application. Users can join or create spaces and have 
conversations in groups.

Initially the project was envisioned as a platform where other members of the ALX software
engineering program would be able to share thoughts and ideas on daily coding assignments or
give tips on these tasks. However, the scope has broadened to include all types of users (ALX
student or not). Regardless, the primary goal still remains the same - sharing thoughs, ideas
and engaging in productive conversations. A problem shared is a problem solved.

## How to get started
- First clone or fork the repo
- Install the necessary requirements using `$ pip install -r requirements.txt`
- Then start the development server with `$ python chat_app.py`
- The project can also be viewed at https://open-mind.onrender.com/login. Please note that this
  url will be changed eventually.

## Technology
### Frontend
- Vanilla Javascript, HTML and CSS

### Backend
- Python as the primary programming language
- Flask web framework
- Flask-socketio for handling chat room communication via the websocket protocol

### Storage/Database
- A simple filestorage at the moment. This will soon be updated to a MySQL relational database

### Server/Deployment
- Cloudflare/Gunicorn
- Use this command to run the Gunicorn server: `$ Gunicorn --worker-class eventlet --threads 4 chat_app:app`

## Screenshots
![Chat page 1](https://github.com/44caleb/OpenMind2/assets/127566561/ee6d960a-a7a9-4fca-8d34-a7f1f3b371fa)
![Chat page 2](https://github.com/44caleb/OpenMind2/assets/127566561/707043b9-1700-4e9c-9d7a-cf825a1eb6c3)
![Join space page](https://github.com/44caleb/OpenMind2/assets/127566561/f8e95b9d-58c5-4b83-96d0-dd173ab4f211)
