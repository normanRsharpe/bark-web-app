Bark Web App
============

Bark Web App is a user-friendly web application that interfaces with the [Bark library](https://github.com/suno-ai/bark) to generate audio from text input. The application is built using Vue.js for the frontend, Flask for the backend, and is hosted on Google Cloud Platform.

Features
--------

*   Generate audio from text input with a variety of voices and languages.
*   Save generated audio as a WAV file.
*   Generate audio with embedded music notes.
*   Utilize voice presets and speaker prompts to generate audio with specific characteristics.

Getting Started
---------------

### Prerequisites

*   Node.js (for Vue.js frontend)
*   Python 3 (for Flask backend)
*   Google Cloud Platform account (for hosting)

### Installation

1.  Clone the repository: `git clone https://github.com/yourusername/bark-web-app.git`

2.  Change to the `frontend` directory and install dependencies: `cd bark-web-app/frontend npm install`

3.  Change to the `backend` directory and install dependencies: `cd ../backend pip install -r requirements.txt`

Development
-----------

### Running the frontend

In the `frontend` directory, run the following command to start the development server: `npm run serve`

### Running the backend

In the `backend` directory, run the following command to start the Flask development server: `export FLASK_APP=app.py flask run`

Deployment
----------

1.  Dockerize the frontend and backend applications.
2.  Set up Google Cloud Platform services, such as Cloud Run and Cloud Storage.
3.  Deploy Docker containers to GCP using Cloud Run.
4.  Configure the custom domain and set up SSL certificates for secure access.
