# WorldWise

WorldWise is a React web application that I have created to learn React. In this project, users can view different pages, interact with a map, and manage their travel experiences.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Key Learnings](#key-learnings)
3. [Getting Started](#getting-started)
4. [Acknowledgement](#acknowledgement)

---

## Project Overview

WorldWise is a single-page web application built with React, Vite, and other technologies. It offers the following main features:

1. **Home Page**: The home page welcomes users and provides navigation to different sections of the application.

2. **Product Page**: This page can contain details about my application.

3. **Pricing Page**: The pricing page displays information about subscription plan.

4. **Login Page**: Users can log in to access their personalized travel data. I've implemented a fake login feature for demonstration purposes.

5. **App Page**: After logging in, users are redirected to the app page, where they can:

    - **View a Map**: Utilizing the Leaflet library, users can see a map with interactive features.
    
    - **Cities and Countries**: The application displays the cities and countries they have visited, likely through a list or markers on the map.
    
    - **Add New City**: Users can interact with the map to add new cities they've visited to their travel list.

---

## Key Learnings

During the development of WorldWise, I've gained valuable experience and knowledge in several areas of web development, including:

1. **React Router**: I've used React Router to manage navigation and routing within my application. This enables users to move between different sections and pages seamlessly.

2. **Lazy Loading**: To optimize bundle size and improve application performance, I've employed lazy loading. This ensures that only the necessary code is loaded when users visit specific routes.

3. **CSS Modules**: I've utilized CSS Modules to create modular, scoped styles for my React components. This approach enhances the maintainability and reusability of styles.

4. **Custom Hooks**: Custom hooks allow me to encapsulate and reuse complex logic across my application. I've created custom hooks to manage data fetching, state management, or other functionalities.

5. **Context with Reducer**: I've employed the React Context API along with a reducer to manage the application's state. This is a powerful method for sharing data and state between components without prop drilling.

6. **Integration of Leaflet Map**: WorldWise integrates the Leaflet library to display interactive maps. I've learned how to add markers and other map features to provide a rich user experience.

---

## Getting Started

Before running the project, make sure you have Node.js and npm installed on your machine.

To get started with WorldWise, follow these steps:

1. Clone the project repository.
  ```
  git clone https://github.com/NikhilMandaliya/WorldWise.git
  ```

2. Navigate to the project directory.
  ```
  cd worldwise
  ```
   
3. Install the required dependencies.
  ```
  npm install
  ```

4. Run the JSON server to simulate a backend with the following command:
  ```
  npm run server
  ```
This will start the JSON server that provides fake API data.

4. Start the development server using Vite with the following command:
  ```
  npm run dev
  ```
This will start the Vite development server.

---

## Acknowledgement

* This project is part of the online course I've taken at Udemy. Thanks to Jonas Schmedtmann for creating this awesome course! Link to the course: [The Ultimate React Course 2023: React, Redux & More](https://www.udemy.com/course/the-ultimate-react-course/)
