# TechTeamUp
This web application aims to provide a collaborative environment for IT enthusiasts, especially newbies, to connect, form teams, and work on practical projects together. The platform facilitates the creation of user profiles, project listings, and team formation, along with a chat system for seamless communication.

## Features

### 1. User Profiles
- Users can create detailed profiles showcasing their skills, experience levels, interests, and goals.
- Profiles can include information such as programming languages, frameworks, and technologies they are familiar with or want to learn.
- Users can upload resumes or portfolios to showcase their work and experience.

### 2. Project Listing and Team Formation
- Users can create and list project ideas they want to work on, including detailed descriptions, objectives, required skills, and technologies involved.
- Other users can browse and search for projects based on their interests, skills, and desired technologies.
- Users can indicate their interest in joining a project, and the project creator can review and approve or reject their requests.
- Project creators can specify the roles or skills required for team members.
- Teams can be formed based on the approved members for a particular project.

### 3. Chat System
- A real-time chat system is integrated for seamless communication and collaboration within project teams.
- Chat rooms or channels can be created for each project team.
- Users can share files, code snippets, and other relevant information within the chat.
- Video or audio conferencing capabilities can be integrated for virtual meetings and discussions (optional).

## Technologies Used
- **Backend**: Django (Python web framework)
- **Frontend**: Vue.js (JavaScript framework)
- **Database**: PostgreSQL (or any other suitable database)
- **Real-time Chat**: Socket.IO (or any other real-time communication library)

## Getting Started

### Prerequisites
- Python 3.x
- Node.js and npm (for Vue.js development)
- PostgreSQL (or any other database you choose to use)

### Installation

1. Clone the repository:\
   `git clone https://github.com/MichaelDecent/TechTeamUp`

2. Set up the backend:\
   `cd backend`\
   `python -m venv env`\
   `source env/bin/activate` # On Windows, use `env\Scripts\activate`\
   `pip install -r requirements.txt`

3. Set up the frontend:\
   `cd ../frontend`\
   `npm install`

4. Configure the database and other settings in the Django project's `settings.py` file.

5. Run database migrations:\
   `cd ../backend`\
   `python manage.py migrate`

6. Start the Django development server:\
   `python manage.py runserver`

7. In a separate terminal, start the Vue.js development server:\
   `cd ../frontend`\
   `npm run serve`
8. Access the application at `http://localhost:8080` (or the appropriate URL provided by the Vue.js development server).

## Contributing
Contributions are welcome! Please follow the standard GitHub workflow:

1. Fork the repository
2. Create a new branch for your feature or bug fix
3. Commit your changes
4. Push to your forked repository
5. Submit a pull request

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgments
- [Django Documentation](https://docs.djangoproject.com/)
- [Vue.js Documentation](https://vuejs.org/v2/guide/)
- [Socket.IO Documentation](https://socket.io/docs/v4/)

## Author
- Michael Nwogha


   
