# events-map-updater
App to update event data and invalidate cache for map.ourrevolution.com.

`fab deploy_event_data` runs every hour on a Heroku dyno with the Heroku scheduler add-on.

## Install
1. Clone repo into your workspace: `git clone git@github.com:Our-Revolution/events-map-updater.git`
1. Change directory: `cd events-map-updater`
1. Make virtual environment: `mkvirtualenv events-map-updater`
1. Enable virtual environment: `workon events-map-updater`
1. Add/export any necessary config variables to your environment
1. Install packages: `pip install -r requirements.txt`

## Usage
1. After you have done all the install steps including environment variables, then run fabric script: `fab deploy_event_data`
