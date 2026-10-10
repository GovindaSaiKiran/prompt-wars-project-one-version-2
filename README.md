# Smart Stadium

Smart Stadium is a crowd management and fan experience web app designed for stadium environments. It helps visitors monitor live match activity, check crowd density across zones, find the fastest routes, access digital tickets, and quickly reach emergency support when needed.

This project was built as part of the PromptWars Challenge, focusing on smarter crowd flow management and a seamless stadium experience for attendees.

## Project Overview

The app provides a mobile-first dashboard for match-day visitors to:
- Track live cricket match updates in real time
- View crowd density by stadium zone
- Estimate wait times for food counters, washrooms, and entry gates
- Navigate to seat locations and nearby facilities
- Access digital tickets and QR-based entry details
- Get transit assistance and route suggestions
- Send emergency SOS alerts for rapid support

## Why This Project Matters

Large stadiums often face challenges such as:
- Heavy crowd congestion near entry gates and facilities
- Difficulty locating seats and amenities
- Poor visibility into waiting times across different zones
- Delayed emergency response during peak hours

Smart Stadium addresses these issues by delivering a unified interface that improves visitor convenience and operational efficiency.

## Key Features

### 1. Live Match Center
- Real-time scoreboard simulation
- Recent ball-by-ball updates
- Team comparison and run rate tracking
- Match status and live insights

### 2. Stadium Navigation
- Map integration with stadium location
- Seat information and gate directions
- Nearby facility listing for food, washrooms, and exits

### 3. Crowd Density Monitoring
- Zone-wise crowd load visualization
- Estimated queue wait times for major service points
- Better crowd flow visibility during peak match times

### 4. Digital Ticket Experience
- Match details, seat assignment, and gate information
- QR-style entry representation for fast access
- Clean and modern ticket layout

### 5. Transit & Route Assistance
- Airport, railway, and bus routes
- Directions to the stadium from major travel points
- Ride-booking reminder and route suggestions

### 6. Emergency Support
- SOS emergency alert section
- Direct contact shortcuts for police, ambulance, and emergency services
- Fast access to help during critical situations

### 7. Fan Profile Section
- Visitor activity and match history
- Personal match attendance insight
- Great for personalized fan engagement

## Tech Stack

- HTML5
- CSS3
- JavaScript
- Firebase (for app configuration and backend integration)
- PWA support (manifest + service worker)
- Docker
- Nginx

## Project Structure

```bash
.
├── app.js                  # Core app logic and UI interactions
├── firebase-config.js      # Firebase setup and configuration
├── index.html              # Main web app structure
├── style.css               # Styling and responsive layout
├── sw.js                   # Service worker for PWA support
├── manifest.json           # Progressive Web App manifest
├── nginx.conf              # Nginx server configuration
├── Dockerfile              # Containerized deployment setup
├── package.json            # NPM scripts and project metadata
├── .eslintrc.json          # Linting configuration
├── README.md               # Project documentation
├── tests/                  # Test files
└── package-lock.json       # Locked dependency versions
```

## Getting Started

### Prerequisites

Before running the project, ensure you have:
- A modern web browser
- Node.js installed (optional, mainly for tooling)
- Python 3 (for local static serving)
- Docker (optional, for containerized deployment)

### Run Locally

Open the project folder and start a local server:

```bash
python -m http.server 8080
```

Then visit:

```bash
http://localhost:8080
```

### Alternative Using Node

```bash
npm install
npm start
```

## Docker Deployment

Build the Docker image:

```bash
docker build -t smart-stadium .
```

Run the container:

```bash
docker run -p 8080:8080 smart-stadium
```

Then open:

```bash
http://localhost:8080
```

## Screens Included

The app includes screens for:
- Live Match
- Stadium Map
- Digital Ticket
- Transit Hub
- Fan Profile
- Emergency Assistance

## Use Case

This project is suitable for:
- Cricket stadiums and sports arenas
- Event venue crowd monitoring
- Smart city event management dashboards
- Visitor assistance and security coordination

## Future Enhancements

Possible improvements include:
- Real Firebase backend integration for live data
- Real-time seat occupancy and crowd analytics
- AI-based crowd prediction and route optimization
- Admin dashboard for stadium operations
- Push notifications and emergency alert automation

## License

This project is currently for educational and challenge demonstration purposes.

## Acknowledgements

- PromptWars Challenge
- Google Cloud-inspired smart stadium experience
- Modern sports venue digital experience design

## Contact

For questions or collaboration opportunities, feel free to connect with the project owner.

---

Smart Stadium brings together technology, crowd intelligence, and a smoother fan experience to redefine how people move, engage, and stay safe in stadium environments.
