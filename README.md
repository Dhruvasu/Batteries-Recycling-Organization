# Batteries Recycling Organization (BRO)

BRO is an organization that serves the purpose of connecting people willing to cautiously dispose off used battries with organizations that offer battery disposal programs. Such organizations can register with BRO and share their location, and users can search such organizations closest to their location. The website uses Google's Maps API to achieve this.

This project was done as part of TOHacks 2019, a 24 hour hackathon held at Ryerson university. It was made successful by a team of 4 members, including @Dhruvasu and @EltonK888.

## Tech Stack used

Python and Flask are used for back-end, with SQLite3 serving as the database. HTML5/CSS3, Bootstrap, JavaScript, and GoogleMaps API is used for the front-end

To successfully run on the local server, ensure that you registered for a GoogleMaps API key, and add the details in place of "YOUR_GOOGLE_MAPS_API_KEY" in app.py

## Dependencies used

Ensure that the following dependencies are installed by doing so:

```bash
$  pip3 install Flask Flask-SQLAlchemy SQLAlchemy flask-googlemaps geocoder
```

## Running on local server

Navigate to the directory with app.py file. Type the following in the console:

```bash
$  python app.py
```

Start the browser and type `http://localhost:8080` in address bar
