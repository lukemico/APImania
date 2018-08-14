# API Integration - Giphy / Ron Swanson / Chuck Norris / 
This application displays a series of API's and how they can interact to return data, images, video etc. This app uses's three separate API's that return a variety of information, to give an insight to the power of accessing API's within applications.


## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.


## Prerequisites
Ensure that you have the following installed on your local machine:

Rails 	[Download Rails](https://guides.rubyonrails.org/getting_started.html)


## Installation 
Clone the repo:

```
git clone https://github.com/lukemico/APImania.git
cd APImania
```

Install any dependancies

```
gem install rack -v 1.6.4
```

then follow instructions in the Running section.


## Steps for starting a Local Server
To start the server, run the following via the Command Line:

```
rails server
```

Open [http://localhost:3000](http://localhost:3000) to view the application in your browser.


## Usage 
* Each API outputs a different type of data.
* Giphy can be searched for a keyword, to return an output.
* Ron Swanson uses a jQuery request to send an update quote at set intervals.
* Chuck Norris uses a jQuery request to send an update quote at set intervals.


## Deployment
View the [Live Demo](https://limitless-wildwood-99984.herokuapp.com/) here.


## Built With
* [Rails](https://guides.rubyonrails.org/getting_started.html) 
* [JavaScript](https://developer.mozilla.org/bm/docs/Web/JavaScript) - to handle the map data and the kendo widget (event date in create event). 
* [HTML](https://www.w3.org/html/) - the framework that pulls together  
* [CSS](https://www.w3.org/Style/CSS/) - used to override some Bootstrap defaults.


API's used
* [Ron Swanson API](https://github.com/jamesseanwright/ron-swanson-quotes) - the database that handles field, range query, and regular expression searches. 
* [Chuck Norris API](https://api.chucknorris.io/) - the de facto standard server framework for Node.js, it is the backend part of the MEAN stack. 
* [Giphy](https://github.com/Giphy/GiphyAPI) - a JavaScript-based front-end web application framework for developing single-page applications. 


## Versioning
GitHub used for versioning. For the versions available, see the tags on this repository.


## Authors
Luke Mico


## License
n/a


## Acknowledgments
[Heroku](https://devcenter.heroku.com/articles) Devcenter



