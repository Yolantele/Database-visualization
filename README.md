## Data Visualisation

Single-page app for representing any database as graphs and charts - helping users interact with databases very easily.

### Key Attributes: 
- Single-page app 
- Data agnostic 
- Visualizes data as tables,  graphs and pie-charts
- Grouping tables by any attribute chosen

### Tech Stack
![screen shot 2018-01-22 at 10 50 36](https://user-images.githubusercontent.com/30931242/35217168-1fc08d74-ff62-11e7-822a-bef7d1c276c7.png)

### Demo
![screen shot 2018-01-22 at 10 47 32](https://user-images.githubusercontent.com/30931242/35217048-b9bf2b98-ff61-11e7-8cf7-369c1410b7ca.png)

### Challenges:
- Working with unfamiliar code - As we tried to gain exposure to different technologies
- Completing unit, service/API and feature tests within a new language using different frameworks, assertion libraries and testrunners - took longer to set up than anticipated
- To include table associations

### Learning:
- Benefits of mobbing - especially when using new technologies
- Think a feature through before starting the development process - we ended up with a feature that worked in the back-end but couldn’t translate it to front-end


### Instructions for use: 
This app connects to a database called 'data_vis_development', using postgres as database. Please see config/db.js and c change it should you need to. Two seed files are provided with this project which you can use to see the app working.

1. Clone the app and seed the database:

```
$ git clone https://github.com/Yolantele/Database-visualization.git
$ cd Database-visualization
$ node seedMovies.js
$ node seedSongs.js
```

2. run the app:

```
$ node index.js
```

3. Visit http://localhost:3000 in your browser.


4. run tests:

```
$ npm test
```


### User stories 

As a User:

```
So that I can understand created databases better
I want to see a visual representation of data in graphs
```
```
So that I can comprehend data better
I want to see data represented in different graph types: for example table, bar-chart
```
```
So that I can use many different databases
I want to plug in any database I choose : movies, songs ect.
```

```
So that I can control the represented data even better
I want to use various data-filters
```
