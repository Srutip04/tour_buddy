<br>
<div align="center">
  <h3 align="center">Tour Buddy</h3>

  <p align="center">  
    <br />
    <a target="_blank" href="https://travel-advisor-sunny.netlify.app/">View Deployment</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project
      </a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
        <li><a href="#features">Features</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
    </li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

An advanced travel companion app using Google Maps API that provides information related to local or international tourists’ destinations.It also provides information  related to restaurants,hotels and attractions based on location. <br/><br/>


### Built With

- **[ReactJS](https://reactjs.org/docs/getting-started.html)** for front-end
- **[Material UI](https://mui.com/)** an open-source React component library which includes a collection of prebuilt components that are ready for use in production to implement  custom design system on top of the components.
- **[Styled Components](https://styled-components.com/)** for styling components
- **[Google Maps API](https://developers.google.com/maps)** for dynamic maps and routes
- **[Rapid API](https://rapidapi.com/hub)** for Travel Advisor API and Weather API
- **[Netlify](https://www.netlify.com/)** used for deploying and hosting the project
- **[Github](https://github.com/)** for CI/CD and git
 <br/>

### Features
- One stop destination where you can plan your whole trip.
- Search and explore new places. It  shows all the locations that are related to that search term.
- Ability to search for places fetching restaurants hotels and attractions based on location from specialized Rapid API 
- Provides information regarding restaurants's,its rating,number of reviews,pricing & types of food they prepare.
- It also gives you attractions you can visit.
- Shows the best hotels in a particular city & its price and ratings.
- It also gives us real time weather information of that specific location you are planning to visit.
 <br/>

## Getting started

```bash
git clone git@github.com:Srutip04/tour_buddy.git
cd tour_buddy
```
Create a .env file in the root directory:

```
REACT_APP_GOOGLE_MAPS_API_KEY= <your_api_key>
REACT_APP_RAPID_API_TRAVEL_API_KEY=<your_api_key>
REACT_APP_RAPID_API_WEATHER_API_KEY=<your_api_key>
```
Run the command in the **root directory  to install all the dependencies**:

```
npm install
npm start
```

