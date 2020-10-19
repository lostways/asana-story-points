# asana-story-points
Counts story points in a given project section

## Setup

`cp config.py.example config.py`

Add your Asana Person Access Token to the config (https://developers.asana.com/docs/personal-access-token)
Add the name of the field that holds your story points to the config. This field must be a number field.

## Install

`pip install -r requirements.txt`

## Run

`python asana-tasks.py`
