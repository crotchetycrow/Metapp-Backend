# Tourist guide web app

## A Flask backend

## Makers Graduates project

## Summary

The app in its current form will be designed as a tourist guide app, allowing users to find events and attractions near them whilst also looking for times and dates.

The app is comprised of two independent programs - a frontend react web app and a backend Python running with Flask.

Currently, the project is in the beginning stage of development and the team is working towards developing the MVP.

The development team:

- [Ben Lawrence](https://github.com/Ben-glitch-cloud)
- [Ed George](https://github.com/eds-101)
- [Jack Hooper](https://github.com/crotchetycrow)
- [John Baxter](https://github.com/john-baxter)
- [Josh Brook](https://github.com/joshuaabrookuk)
- [Phil Smithies](https://github.com/philsmithies)
- [Zsuzsanna Ver](https://github.com/MrsVer)

## To Use

### To run this project
Prerequisites:\
You should have `python3` and `pip3`  installed\
cd into the repo and create a virtual environment:
```
python3 -m venv metapp_venv
source metapp_venv/bin/activate
```
and install these libaries:

```
pip3 install flask python-dotenv
```

To deactivate the virtual environment type:
```
deactivate
```

#### Development Mode

## Tech Stack

- Python
- Flask

## Development Summary

The team is currently working on developing this tourist guide application. We are working throughout in an Agile manner, running one week sprints with weekly stand-ups and retros. We use a Trello board to manage our work and ensure we had visiual representation of our activities.

In the initial stages of the project we did a group brainstorm to identify ideas for the project and concluded we wanted to build a frontend React application which interacted with a Python backend. A common learning outcome for this project was to consolidate our learning from Makers and develop our portfolios.

We choose Python and Flask for our backend to help develop our learning, specifically, it was an opportunity for us to develop the skills we learnt from Makers and to build on existing Python skills that some of us already have. Flask is also a good web framework for building web application due to its flexibility and customisation capabilities.

We defined and completed out MVP by the third stand up of the project, following the principle of building the simplest features our project needed to function.

### MVP

As it stands, the MVP currently consists of these features:

- User's ability to use a search function to search for events
- Events are based in London only
- Events are listed with details and images, sorted by proximity and date
- Events are shown for the next 7 days from date of search

### User Stories

## MVP

```
As a back-end dev
So that I can show the user things to do
I want to receive an address (or postcode etc.) from the search bar
```

```
As a back-end dev
So that I can show the user events around their location
I want to access the API and find events in their approximate area
(based on a square with the user at the centre)
```

```
As a back-end dev
So that I can present the user with their search results
I want to sort the results primarily by date, secondarily by distance from user
```

```
As a back-end dev
So that I can optimise the user experience
I want to return a sorted list of stuff
```

```
As a back-end dev
So that I can filter the list of events
I want to enable users to select a `subcategory` after conducting their initial search
```

```
As a back-end dev
So that I can allow users to see upcoming events
I want to limit the search results to a 7-day time frame (as default)
```

## Stretch goals

```
As a back-end dev
So that I can enable users to find interesting events
I want to allow them to sign up to the app
```

```
As a back-end dev
So that I can enable users to remember their upcoming events
I want to allow them to save their selected events to their account
```

```
As a back-end dev
So that I can allow users to visualise where their events are
I want to be able to show them a map with the locations of their searched events pinned
```

```
As a back-end dev
So that I can allow users to visualise where their events are
I want to be able to show them a map with the locations of their saved events pinned
```

```
As a back-end dev
So that I can improve the user's search results
I want to restrict their range to a circle with them at the centre
```

