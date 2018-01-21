## Data visualisation
A single-page app for representing any Postgres database as graphs, charts or tables.

![img](/img/screenshot.png)

## How to use
This app uses Postgres as its database so you will need to have that installed. By default this app connects to a database called 'data_vis_development'. This is defined in config/db.js and can be changed according to your needs. Two seed files are provided with this project which you can use to see the app working.

First clone the app and seed the database:
```
$ git clone https://github.com/cazwazacz/Database-visualization.git
$ cd Database-visualization
$ node seedMovies.js
$ node seedSongs.js
```

To run the app:
```
$ node index.js
```
Visit http://localhost:3000 in your browser.

For tests, run:

```
$ npm test
```

## User Stories

```
As a user
So that I can understand created databases better
I want to see a visual representation of data in graphs
```
```
As a User
So that I can comprehend data better
I want to see data represented in different graph types: for example table, bar-chart
```
```
As a user
So that I can use many different databases
I want to plug in any database I choose : movies, songs ect.
```

```
As a User
So that I can control the represented data even better
I want to use various data-filters
```
