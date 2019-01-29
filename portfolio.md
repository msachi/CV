# Portfolio: Marko Sustarsic

[Real-world projects](#real-world-projects) | [Bootcamp projects](#founders-coders-bootcamp-projects) | [Personal projects](#personal-projects)

## Real-world projects

### Night Zookeeper Teacher's Settings ([website](https://www.nightzookeeper.com/edu))

<p float="left">
  <img src="snapshots/settings/tablet-1.png" height="320" style="margin-right: 10px; margin-bottom: 10px;"/>
  <img src="snapshots/settings/tablet-2.png" height="320" style="margin-right: 10px; margin-bottom: 10px;"/>
  <img src="snapshots/settings/tablet-3.png" height="320" style="margin-right: 10px; margin-bottom: 10px;"/>
  <img src="snapshots/settings/tablet-4.png" height="320" style="margin-right: 10px; margin-bottom: 10px;"/>
  <img src="snapshots/settings/tablet-5.png" height="320" style="margin-right: 10px; margin-bottom: 10px;"/>
  <img src="snapshots/settings/tablet-6.png" height="320" style="margin-right: 10px; margin-bottom: 10px;"/>
</p>


### Night Zookeeper Reading Light ([website](https://www.nightzookeeper.com/edu))

A Night Zookeeper single-page application that allows children to keep track of their reading. Children can find their book using a Google Books API-powered search tool, and then log their reading time and write short summaries or longer reviews. Teachers can review and comment on the writing. Includes fun animations that progress with the increasing reading time. Desktop and tablet friendly.

**Tech stack**: HTML, CSS, JavaScript (ES6), React, Styled components, Storybook, GraphQL, Apollo, NodeJS, MongoDB  
**Co-developers**: Night Zookeeper team

<p float="left">
  <img src="snapshots/reading-light/tablet-1.png" height="320" style="margin-right: 10px; margin-bottom: 10px;"/>
  <img src="snapshots/reading-light/tablet-2.png" height="320" style="margin-right: 10px; margin-bottom: 10px;"/>
  <img src="snapshots/reading-light/tablet-4.png" height="370" style="margin-right: 10px;"/>
  <img src="snapshots/reading-light/tablet-5.png" height="370" style="margin-right: 10px;"/>
  <img src="snapshots/reading-light/tablet-6.png" height="370" style="margin-right: 10px;"/>
</p>

### Night Zookeeper Class Blog ([website](https://www.nightzookeeper.com/edu))

A Night Zookeeper single-page application that is used as a blog for all the class creations. Works similarly to the Kid's Profile (below) and uses some of the same React components, but has more complex sorting and filtering options. The allowed views and functionality are determined dynamically based on the logged-in user role (student vs. teacher) and which class and school they belong to. Fully responsive.

**Tech stack**: HTML, CSS, JavaScript (ES6), React, Styled components, Storybook, GraphQL, Apollo, NodeJS, MongoDB  
**Co-developers**: Night Zookeeper team

<p float="left">
  <img src="snapshots/class-blog/tablet-1.png" height="370" style="margin-bottom: 10px; margin-right: 10px;"/>
  <img src="snapshots/class-blog/tablet-2.png" height="370" style="margin-bottom: 10px; margin-right: 10px;"/>
  <img src="snapshots/class-blog/tablet-3.png" height="370" style="margin-bottom: 10px;"/></p>

### Night Zookeeper Kid's Profile ([website](https://www.nightzookeeper.com/edu))

A Night Zookeeper single-page application that allows children to see of all their stats and their writing, drawings, lessons and comments. Includes a number of filters and subfilters for each content category, as well as a search tool. Data is loaded dynamically and in small chunks using GraphQL queries, with infinite scrolling implemented for all content lists. Fully responsive.

**Tech stack**: HTML, CSS, JavaScript (ES6), React, Styled components, Storybook, GraphQL, Apollo, NodeJS, MongoDB  
**Co-developers**: Night Zookeeper team

<p float="left">
  <img src="snapshots/profile/tablet-1.png" height="320" style="margin-bottom: 10px; margin-right: 10px;"/>
  <img src="snapshots/profile/tablet-2.png" height="320" style="margin-bottom: 10px;"/>
  <img src="snapshots/profile/mobile-1.png" height="400" style="margin-right: 10px;"/>
  <img src="snapshots/profile/mobile-2.png" height="400" style="margin-right: 10px;"/>
  <img src="snapshots/profile/mobile-3.png" height="400" style="margin-right: 10px;"/>
</p>

### Night Zookeeper Kid's Menu ([website](https://www.nightzookeeper.com/edu))

The landing page for children when they log into Night Zookeeper, where they can choose from a number of activities.

**Tech stack**: HTML, CSS, JavaScript (ES6), React, Styled components, Storybook  
**Co-developers**: Night Zookeeper team

<p float="left">
  <img src="snapshots/kids-menu/tablet-1.png" height="500" style="margin-right: 15px;"/>
  <img src="snapshots/kids-menu/tablet-2.png" height="500"/>
</p>

### Cannes Lions / Eurobest delegate system ([website](https://www.eurobest.com/pass-manager#/))

A dynamic single-page application used as the main e-commerce platform for purchasing and managing passes for Cannes Lions and Eurobest festivals. Implements complex business logic and ties together a range of functionalities, including handling of delegate information, uploading of photos and ID documents, handling of URL invites and of special delegate passes (press and jury), managing of booking contacts, purchasing of passes via bank transfer or credit card, replacement of delegates, pass upgrades and visa letter requests.

Uses small and reusable React components, Redux and Immutable.js for managing the state and Redux sagas for asynchronicity. Renders forms dynamically using JSON schemas obtained from the API, and applies schema-defined validation rules. Uses modals and portals to display overlays and accordions, and includes complex CSS animations for card flipping effects. Tested using Jest, Nightwatch and a manual testing framework that recreates the DOM in Node.js.

**Tech stack**: HTML, CSS, SASS, JavaScript (ES6), React, Redux, Immutable.js  
**Co-developers**: Cannes Lions team

<p float="left">
  <img src="snapshots/passmanager-1.png" height="400"/>
  <img src="snapshots/passmanager-2.png" height="400"/>
  <img src="snapshots/passmanager-3.png" height="400"/>
  <img src="snapshots/passmanager-4.png" height="400"/>
  <img src="snapshots/passmanager-5.png" height="400"/>
</p>

### Eurobest pass picker ([website](https://www.eurobest.com/passes#/))

A dynamic, mobile-friendly single-page application that was used to advertise passes for the Eurobest festival. Uses cookies to store the basket information locally and integrate with pass manager (see above).

**Tech stack**: HTML, CSS, SASS, JavaScript (ES6), React, Redux, Immutable.js  
**Co-developers**: Cannes Lions team

<p float="left">
  <img src="snapshots/passpicker.png" height="400"/>
</p>

### Cannes Lions planner

A dynamic, mobile-friendly single-page application that was used by Cannes Lions festival attendees prior to and during the festival. Uses fuzzy searching, filtering and CSS animations.

**Tech stack**: HTML, CSS, SASS, JavaScript (ES6), React, Redux, Immutable.js  
**Co-developers**: Cannes Lions team  

<p float="left">
  <img src="snapshots/planner-1.png" height="350"/>
  <img src="snapshots/planner-2.png" height="350"/>
</p>

### Centrepoint alumni network ([GitHub](https://github.com/lucy-marko/centrepoint) | [website](https://centrepoint.herokuapp.com/))

A mobile-first web app that will allow former Centrepoint residents access their Centrepoint address history and information that they may require for their new tenancy agreements. Implements Yoti, a digital ID technology that aims to make personal identification simpler and more secure.

**Tech stack**: HTML, CSS, Materialize, JavaScript, Node.js, hapi.js, PostgreSQL  
**Co-developer**: Lucy Monie, **partners**: Centrepoint, Outlandish, Yoti  

<p float="left">
  <img src="snapshots/centrepoint-1.png" height="350"/>
  <img src="snapshots/centrepoint-2.png" height="350"/>
  <img src="snapshots/centrepoint-3.png" height="350"/>
</p>

### SocialUp ([GitHub](https://github.com/CYPIAPT-LNDSE/social-up) | [website](https://cypiapt-lndse.github.io/social-up/))

A Chrome extension and desktop web app that helps young people deal with low self-esteem induced by social media. Uses evidence-based cognitive behavioural therapy (CBT) approaches.  

**Tech stack**: HTML, CSS, Bootstrap, JavaScript, jQuery  
**Co-developer**: Marina Sideri, **partners**: Matteo Turco, Anna Freud centre

_Please note: This is currently a prototype. We are looking for funding to develop it further._

<p float="left">
  <img src="snapshots/socialup-1.png" height="230"/>
  <img src="snapshots/socialup-2.png" height="230"/>
</p>

<p float="left">
  <img src="snapshots/socialup-3.png" height="230"/>
  <img src="snapshots/socialup-4.png" height="230"/>
</p>

## Founders & Coders bootcamp projects

_Note: Most of these projects were built in 2-3 days, as learning exercises to implement studied technologies, and not with the intent of building commercial products. The projects were built in teams of 2 or 4 people (using pair programming), and so include other people's work._

### Dishboard ([GitHub](https://github.com/seals-of-approval/dish-board))

A dashboard for Founders & Coders members to easily view all GitHub issues from F&C organisation.

**Tech stack**: HTML, CSS, JavaScript, hapi.js, Handlebars, OAuth, hapi-auth-cookie, JWTs

<p float="left">
  <img src="snapshots/dishboard-1.png" height="260"/>
  <img src="snapshots/dishboard-2.png" height="260"/>
  <img src="snapshots/dishboard-3.png" height="260"/>
</p>

### OCD-B - Open Code DataBase ([GitHub](https://github.com/NodeGroup2/OCD-B))

A content management system for sharing and reviewing coding resources.

**Tech stack**: HTML, CSS, JavaScript, hapi.js, Handlebars, PostgreSQL  
**Testing**: Nightwatch

<p float="left">
  <img src="snapshots/ocdb-1.png" height="260"/>
  <img src="snapshots/ocdb-2.png" height="260"/>
</p>

<p float="left">
  <img src="snapshots/ocdb-3.png" height="270"/>
  <img src="snapshots/ocdb-4.png" height="270"/>
</p>

### GRAGS - Get Recipes And GrocerieS ([GitHub](https://github.com/NodeGroup2/GRAGS) | [website](https://grags.herokuapp.com/))

A web app that searches for recipes and provides grocery shopping lists.

**Tech stack**: HTML, CSS, JavaScript, hapi.js, Handlebars  
**API list**: Recipe puppy, Tesco  
**Testing**: qUnit, Tape

<p float="left">
  <img src="snapshots/grags-1.png" height="400"/>
  <img src="snapshots/grags-2.png" height="400"/>
</p>

### Text Toads ([GitHub](https://github.com/NodeGroup2/autocomplete-project) | [website](https://nodetojoy-autocomplete.herokuapp.com/))

A word finder with autocomplete functionality and Google search redirection.

**Tech stack**: HTML, CSS, JavaScript, Node.js  
**Testing**: qUnit, Tape

<img src="snapshots/text-toads.png" width="420"/>

### Machinspirator ([GitHub](https://github.com/FAC9/gitbusters_api))

A web app that uses a machine learning API to interpret a given image, then suggests a song, a video and an article based on the image content.

**Tech stack**: HTML, CSS, JavaScript  
**API list**: Unsplash It, Microsoft Computer Vision, Guardian, musixmatch  
**Testing**: qUnit


<p float="left">
  <img src="snapshots/machinspirator-0.png" width="420"/>
  <img src="snapshots/machinspirator-1.png" width="420"/>
</p>

<p float="left">
  <img src="snapshots/machinspirator-2.png" width="420"/>
  <img src="snapshots/machinspirator-3.png" width="420"/>
</p>

### Stopwatch ([GitHub](https://github.com/stevehopkinson/steve-marko-stopwatch) | [website](https://stevehopkinson.github.io/steve-marko-stopwatch/))

A digital and analogue stopwatch app. Allows multiple stopwatches to be run simultaneously.

**Tech stack**: HTML, CSS, JavaScript  
**Testing**: Jasmine

<img src="snapshots/stopwatch.png" width="420"/>

### Team portfolio ([GitHub](https://github.com/FAC9/nomastew-blog) | [website](https://fac9.github.io/nomastew-blog/))

A template for a portfolio and blog, to be used by our project team at F&C.

**Tech stack**: HTML, CSS

<p float="left">
  <img src="snapshots/team-portfolio-1.png" height="300"/>
  <img src="snapshots/team-portfolio-2.png" height="300"/>
</p>

## Personal projects

### Marble game ([GitHub](https://github.com/msachi/marble-game) | [website](https://msachi.github.io/marble-game/))

A simple mobile web game, made as an exercise in learning the `deviceorientation` API.

**Tech stack**: HTML, CSS, JavaScript, jQuery

<p float="left">
  <img src="snapshots/marble-game-1.png" width="150"/>
  <img src="snapshots/marble-game-2.png" width="150"/>
</p>

### Weather app ([GitHub](https://github.com/msachi/weather-app))

An app that displays local weather.

**Tech stack**: HTML, CSS, JavaScript  
**API list**: OpenWeatherMap

<img src="snapshots/weather-1.png" width="350"/>
