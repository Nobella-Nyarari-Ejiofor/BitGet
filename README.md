# 𝓑𝓲𝓽𝓰𝓮𝓽 𝓢𝓮𝓪𝓻𝓬𝓱🔥

Custom Youtube search and videoplayer.

# How it works

1. It shows top 12 youtube video result of your search.

2. On clicking at any video, it opens a new page containing the embedded video and a button to redirect to youtube page of the same video.

# Features:

Shows title, total no. of views, thumbnail and the video uploaded date.

# How to Use

# Initialize the project

# Create and activate a virtualenv:

1. `virtualenv venv`. This will a create a vitual environment called "venv" that helps with controlling dependencies.(For windows run `mkvirtualenv venv`)
2. `source venv/bin/activate`.( For windows run `workon venv` )

# Install dependencies:

(while in the activated virtual environment)

```bash
pip install -r requirements.txt
```

NOTE: After installing dependencies, pip-tools is also installed. You can now use it to manage package dependencies of your project.

Add a new package to requirements.txt and run the following command to auto-update requirements.txt file

```bash
pip freeze > requirements.txt
```

# Set Your API key

Open the Youtube_Search/settings.py file and change YourAPIKey with 'Google developer genereated API of Youtube Data API v3' here:

```bash
YOUTUBE_API_KEY = 'YourAPIKey'
```

##### Run the server:

```bash
python3 manage.py runserver
```
