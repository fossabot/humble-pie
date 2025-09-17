HumblePie
==============

A simple Passtools testing app built with [Flask](http://flask.pocoo.org/).

### [Link: Example HumblePie Server](http://protected-castle-1940.herokuapp.com/)

## Running HumblePie
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Furbanairship%2Fhumble-pie.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Furbanairship%2Fhumble-pie?ref=badge_shield)


Install Flask using Pip: "pip install Flask". From the squarepig directory run "python app.py". Navigate your web browser to localhost:5000. 

## Deploying to Heroku. 

A "requirements.txt" is included for easy deployment to [Heroku](https://devcenter.heroku.com/).

## Resources 

* See [passtools-python README](https://github.com/tello/passtools-python/) for more information on setting up the Passtools-Python library. 
* Indexed documentation for the python SDK is available at [http://tello.github.com/passtools-python/](http://tello.github.com/passtools-python/).

## Features

### Template API Methods

* Retrieve list of templates
* View detailed profile for each template

### Pass API Methods

* Create pass from a template
* Retrieve list of passes
* View detailed profile for each pass
* Download pass

## Roadmap

* Simple UI for editing template fields and pass fields, and saving these changes via the `update_pass` view handler. 
* SQLite database for saving preferences, such as the API key used for making requests. 
* More features that lend themselves to real-world use cases - analytics, etc.





## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Furbanairship%2Fhumble-pie.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Furbanairship%2Fhumble-pie?ref=badge_large)