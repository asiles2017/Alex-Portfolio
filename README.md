## Website Performance Optimization portfolio project

Your challenge, if you wish to accept it (and we sure hope you will), is to optimize this online portfolio for speed! In particular, optimize the critical rendering path and make this page render as quickly as possible by applying the techniques you've picked up in the [Critical Rendering Path course](https://www.udacity.com/course/ud884).

To get started, check out the repository and inspect the code.

### Getting started

#### Part 1: Optimize PageSpeed Insights score for index.html

Some useful tips to help you get started:

1. Check out the repository
1. To inspect the site on your phone, you can run a local server

  ```bash
  $> cd /path/to/your-project-folder
  $> python -m SimpleHTTPServer 8080
  ```

1. Open a browser and visit localhost:8080
1. Download and install [ngrok](https://ngrok.com/) to the top-level of your project directory to make your local server accessible remotely.

  ``` bash
  $> cd /path/to/your-project-folder
  $> ./ngrok http 8080
  ```

1. Copy the public URL ngrok gives you and try running it through PageSpeed Insights! Optional: [More on integrating ngrok, Grunt and PageSpeed.](http://www.jamescryer.com/2014/06/12/grunt-pagespeed-and-ngrok-locally-testing/)

Profile, optimize, measure... and then lather, rinse, and repeat. Good luck!
## Website Performance Optimization portfolio project

### How To Run:

To access the Website: https://asiles2017.github.io/Alex-Portfolio/. This is a Github Webpages repository.


### Optimizations: 

#### On Index.html

* Assigned Media=print to print.css
* Set async to Javascripts (analytics.js and perfmatters.js)
* Changed image size pizzeria.jpg
* Changed to async to inline Javascript
* Added inline style instead of style.css file
* Removed link to Fonts (bad performance)
* Moved javascript links at the end

#### On main.js

* Fixed 2 syncronous layouts on functions *updatePositions()* and *resizePizzas()*.
