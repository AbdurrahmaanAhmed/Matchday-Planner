# Weekend City Break – Matchday Experience Platform

The Weekend City Break project is a prototype web platform designed to improve the matchday experience for travelling football fans. It helps supporters visiting unfamiliar cities easily plan their journey, discover social hotspots, and keep up with fixtures — making away days smoother and more enjoyable.


## Preview
<img width="1918" height="967" alt="image" src="https://github.com/user-attachments/assets/22328ebd-90cf-4136-a1d0-9b8c695669c3" />



**🌟 Key Features:**

**Smart Route Recommendation System**
  Enter your starting point and travel method (train/bus, walking, or driving).
  
  Get live, optimised routes using the Google Maps Directions API.
  
  Dynamic updates based on traffic and transit conditions.
  
  <img width="1920" height="963" alt="image" src="https://github.com/user-attachments/assets/9d64c441-21b8-41d5-b4fc-75d8c9cb6a69" />

**Fan Hotspots Map**

  Explore pubs, restaurants, and social hubs near stadiums.
  
  Use multiple filters (rating, atmosphere, refreshments, home/away suitability).
  
  View detailed venue info with ratings, hours, and matchday highlights.
  
  Save favourite locations for easy access later.
  
  <img width="1920" height="966" alt="image" src="https://github.com/user-attachments/assets/05e6a418-4eaf-4f35-a81f-158342ca0413" />


**Matchday Planner**

  Calendar with fixtures (date & time).
  
  Integrated with the travel planner for match-specific journeys.

**Login/Sign-up (Prototype)**

  Basic authentication interface to simulate user flow.
  
  Prepares groundwork for future features like saving plans & preferences.
  
  <img width="1914" height="964" alt="image" src="https://github.com/user-attachments/assets/43ef17af-b8ad-482b-a5e3-ba56dc5674fc" />


**🛠️Tech Stack**

**Frontend:**

  HTML5, CSS3, JavaScript (Vanilla)

**Libraries & APIs:**

  Bootstrap 5 (responsive layouts & components)
  
  Font Awesome (icons)
  
  Google Maps API (directions, markers, dynamic maps)

**Storage:** 
  
  LocalStorage (saving favourites)
  
  No backend (frontend-only prototype for now)

**🎯 Why This Project?**

Football fans often struggle when travelling to away matches:
  Where to go before/after games?
  How to get to the stadium?
  Which routes are safest and fastest?
  
This project addresses those challenges with a simple, interactive, and practical tool.

**🔍 Future Improvements**
  Backend integration for real user accounts & saved preferences.
  Accessibility enhancements (scalable text, high-contrast mode, screen reader support).
  Expanded features like stadium seating previews, ticketing, and user reviews.
  Testing with fans from multiple clubs for broader insights


# Setup
**1. Clone the Repository**

  git clone https://github.com/your-username/Matchday-Planner.git
  
  cd Mathday-Planner

**2. Open the Project**

  Navigate to the project folder.
  
  Open the index.html file in your browser (double-click or right-click → Open with Browser).

  Alternatively download the file to your device and open wih visual studio code, then on the bottom right press go live and use in your preferred browser

**3. Enable Google Maps API**

  This project uses the Google Maps Directions API.
  
  To make the interactive maps work:
  
  Get a free API key from Google Cloud Console.
  
  Replace the placeholder API key in script tags inside index.html with your own key.
  
  <script src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY&libraries=places"></script>

**4. Explore the Features**

  Matchday Planner: Get optimised routes to the stadium.
  
  Fan Hotspots: Discover pubs & restaurants nearby with filters.
  
  Login/Sign-up (prototype): Try out the basic authentication flow.
  
⚠️ Note: This is a frontend prototype only — no backend, so login/sign-up does not store data.
