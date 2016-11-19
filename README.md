# online-house-selling

OHS is a simple web application that lets you add, edit, view and delete a house ad as well as locates your house with google maps location search.

##### This is one of my Hacktiv8's project using:
- Node.js v6+
- Express
- MongoDB
- Mongoose
- JQuery and Ajax
- Google Maps API

## Installation
- Clone the repo: `git clone https://github.com/tevinstein/online-house-selling.git`

#### In the folder *server*
- Install packages: `npm install`
- Start the server: `npm start`

#### In the folder *client*
- Preview the html file in your browser by opening **index.html** or run live-server if you have it installed `live-server`

## Restful API
| URL       | Method | Description     |
|-----------|--------|-----------------|
| /api/houses     | GET    | Shows all house |
| /api/houses     | POST   | Creates a house  |
| /api/houses/:id | GET    | Shows a house    |
| /api/houses/:id | DELETE | Deletes a house  |
| /api/houses/:id | PUT    | Updates a house  |

## Screenshots

[![Online House Selling](http://i.imgur.com/qq40umZ.png "Online House Selling")](http://i.imgur.com/qq40umZ.png "Online House Selling")