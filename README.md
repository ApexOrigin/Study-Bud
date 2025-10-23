<div align="center">
<img width="30%" src="https://user-images.githubusercontent.com/72341453/134747028-7e2d90cc-a92f-4f66-815e-54a0d50cca54.PNG">

# StudyBuddy

</div>

StudyBuddy is a Django-based discussion platform where users can create study rooms, participate in discussions, and connect with other learners based on topics of interest.

## 🚀 Features

- User authentication with email
- Create and join study rooms
- Topic-based room organization
- Real-time messaging in rooms
- User profiles with avatars
- Activity feed
- Search functionality for rooms and topics
- RESTful API integration
- Mobile-responsive design

## 💻 Tech Stack

- **Backend**: Django 5.2.7
- **Frontend**: HTML, CSS, JavaScript
- **Database**: SQLite
- **API**: Django Rest Framework
- **Authentication**: Django Authentication System

## 🛠️ Installation Steps

1. Clone the repository

```bash
git clone https://github.com/divanov11/studybuddy.git
```

2. Create a virtual environment

```bash
python -m venv env
```

3. Activate the virtual environment

```bash
# On Windows
env\Scripts\activate

# On Unix or MacOS
source env/bin/activate
```

4. Install dependencies

```bash
pip install -r requirements.txt
```

5. Run migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

6. Create a superuser

```bash
python manage.py createsuperuser
```

7. Run the server

```bash
python manage.py runserver
```

Visit `http://127.0.0.1:8000/` in your browser

## 🏗️ Project Structure

```
studybuddy/
├── base/                   # Main application directory
│   ├── api/               # API endpoints
│   ├── migrations/        # Database migrations
│   ├── templates/         # Application templates
│   ├── models.py          # Database models
│   ├── views.py           # View logic
│   ├── urls.py           # URL configurations
│   └── forms.py          # Form definitions
├── static/                # Static files
│   ├── images/           # Image assets
│   ├── js/               # JavaScript files
│   └── styles/           # CSS files
├── templates/             # Base templates
├── manage.py             # Django management script
└── requirements.txt      # Project dependencies
```

## 🌟 Key Features Explained

### Room Management

- Create, update, and delete study rooms
- Join rooms as a participant
- Real-time messaging in rooms

### Topic Organization

- Browse rooms by topics
- Search functionality across rooms and topics
- Topic-based filtering

### User Profiles

- Customizable user profiles
- Avatar upload
- Activity tracking
- Room participation history

### 📱 App Preview

<table width="100%"> 
<tr>
<td width="50%">      
&nbsp; 
<br>
<p align="center">
  Feed Home
</p>
<img src="https://user-images.githubusercontent.com/72341453/134747262-0a92233d-8010-40f8-84c5-8d94895aac44.PNG">
</td> 
<td width="50%">
<br>
<p align="center">
  Room Conversation Preview
</p>
<img src="https://user-images.githubusercontent.com/72341453/134747155-3ca5b55f-b064-4741-aeae-abe90bddf41e.PNG">  
</td>
</table>

## 📝 Models

- **User**: Custom user model with email authentication
- **Room**: Discussion rooms with host, topic, and participants
- **Topic**: Categories for rooms
- **Message**: Chat messages within rooms

## 🔄 API Endpoints

- `/api/rooms/`: List and create rooms
- `/api/topics/`: List topics
- `/api/messages/`: List messages

## 📜 License

This project is licensed under the MIT License - see the LICENSE file for details

## 🙏 Acknowledgments

- Django documentation
- Django Rest Framework
- Bootstrap for styling inspiration
