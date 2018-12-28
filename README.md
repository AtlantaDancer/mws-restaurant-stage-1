# Mobile Web Specialist Certification Course
---
#### _Three Stage Course Material Project - Restaurant Reviews_

## Project Overview: Stage 1

For the **Restaurant Reviews** projects, I incrementally converted a static webpage to a mobile-ready web application. 

In **Stage One**, took existing static design that lacked accessibility and converted the design to be a responsive progressive web application.
  1. Converted webpages to be responsive on different sized displays and accessible for screen reader use. 
  2. I also added a service worker to begin the process of creating a seamless offline experience for your users.

In **Stage Two**, modified code from _Stage 1_ to utilize an existing web service (mws-restaurant-review-Stage-2) to retrieve restaurant review data.  
  1. updated to utilize web server for restaurant data
  2. Introduced caching of review data by the service worker.  
  3. Improved performance to meet rudimentary lighthouse scores. Progressive Web Application >90, Accessibility >90 and Performance >70.

in **Stage Three** modified code from _Stage 2_ to utilize existing web service (mws-restaurant-review-stage-3) to retrieve restaurant data and restaurant reviews.  
  1. Update to utilize new web services for restaurant and review data 
  2. Add a form to allow users to submit their own reviews.
  3. Add functionality to defer submission of the form until connection is re-established.
  4. Follow the recommendations provided by Lighthouse to achieve the required performance targets.  Progressive Web Application >90, Accessibility >90 and Performance >90.
  

### How to run the code

1. In this folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer. 

In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8080` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python3 -m http.server 8080`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.

2. Clone the mws-restaurant-review-stage-3 and run the sails server to start the required web services.

3. With your server running, visit the site: `http://localhost:8080`, and look around for a bit to see what the current experience looks like.


## Leaflet.js and Mapbox:

This repository uses [leafletjs](https://leafletjs.com/) with [Mapbox](https://www.mapbox.com/). You need to replace `<your MAPBOX API KEY HERE>` with a token from [Mapbox](https://www.mapbox.com/). Mapbox is free to use, and does not require any payment information. 

### Note about ES6

Most of the code in this project has been written to the ES6 JavaScript specification for compatibility with modern web browsers and future proofing JavaScript code. As much as possible, try to maintain use of ES6 in any additional JavaScript you write. 

