# URL Shortener APP - short.io
### This tool takes any url and converts it into a shorter, more readable url

## Installation and Usage
### Installation
- Clone this repo
- `cd` into folder
- Run `pipenv shell`
- Run `pipenv install -r requirements.txt`

### Usage
- Run `python main.py` to run the app!

## .env file contents
```
SECRET_KEY=verysecretkey
DATABASE_URL=sqlite:///shorty.db
APP_SETTINGS=config.DevelopmentConfig
FLASK_APP=core
```

## Wins and Challenges
### Wins
- App works as intended
- Shortened URLs are stored in a SQL database

### Challenges
- Struggled to deploy to a live server
- Couldnt change server-name/domain-name to short.io
