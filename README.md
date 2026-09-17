# Smart India Hackathon Workshop

## Date: 17/09/26

## Register Number: 212223040146

## Name: POOJA S

## Problem Title

SIH 1710: Enhancing Navigation for Railway Station Facilities and Locations

## Problem Description

Railway stations are complex environments with numerous facilities and locations such as ticket counters, platforms, restrooms, food courts, and waiting areas. Passengers often face difficulties in navigating these spaces, especially in large or unfamiliar stations.

The problem involves developing a comprehensive navigation solution for railway stations that helps passengers locate various facilities and destinations within the station premises.

The system provides detailed maps, step-by-step directions, accessibility options, voice-guided navigation, and digital kiosk support.

The main aim is to reduce passenger confusion, save time, improve accessibility, and provide a better passenger experience.

## Problem Creator's Organization

Ministry of Railway

## Idea

### RailNav AI – Smart Indoor Railway Station Navigation System

RailNav AI is a smart indoor navigation system designed to help passengers quickly locate platforms, ticket counters, restrooms, food courts, waiting halls, lifts, escalators, exits, and other railway station facilities.

The system provides:

- Interactive station maps
- Facility search
- Step-by-step navigation
- Accessibility-aware routes
- Voice guidance
- Digital kiosk support
- Real-time facility updates

The passenger can select their current location and destination, and the system provides a suitable route.

## Proposed Solution / Architecture Diagram

```text
                  ┌─────────────────────────┐
                  │       PASSENGER         │
                  │   Mobile App / Kiosk    │
                  └────────────┬────────────┘
                               │
                               ▼
                  ┌─────────────────────────┐
                  │      USER INPUT         │
                  │                         │
                  │ • Current Location      │
                  │ • Destination           │
                  │ • Accessibility Needs   │
                  └────────────┬────────────┘
                               │
                               ▼
                  ┌─────────────────────────┐
                  │   NAVIGATION ENGINE     │
                  │                         │
                  │ • Route Calculation     │
                  │ • Accessibility Check   │
                  │ • Facility Search       │
                  └────────────┬────────────┘
                               │
                    ┌──────────┴──────────┐
                    ▼                     ▼
          ┌──────────────────┐   ┌──────────────────┐
          │   STATION MAP    │   │  REAL-TIME DATA  │
          │                  │   │                  │
          │ • Platforms      │   │ • Facility Status│
          │ • Facilities     │   │ • Closures       │
          │ • Lifts          │   │ • Updates        │
          │ • Stairs         │   │ • Platform Info  │
          └────────┬─────────┘   └────────┬─────────┘
                   │                      │
                   └──────────┬───────────┘
                              ▼
                  ┌─────────────────────────┐
                  │    NAVIGATION ROUTE     │
                  │                         │
                  │ • Shortest Route        │
                  │ • Accessible Route      │
                  │ • Easy Route            │
                  └────────────┬────────────┘
                               │
                               ▼
                  ┌─────────────────────────┐
                  │        OUTPUT            │
                  │                         │
                  │ • Interactive Map       │
                  │ • Step-by-Step Directions│
                  │ • Voice Guidance         │
                  │ • Mobile Navigation     │
                  │ • Digital Kiosk          │
                  └─────────────────────────┘
```
## Use Cases

1. Passenger Navigation

A passenger enters:

"Platform 7"

The system identifies the current location and displays the route to Platform 7.

2. Facility Search

The passenger can search for:

Restroom  
Ticket counter  
Food court  
Waiting hall  
Drinking water  
Medical facility  
Lift  
Escalator  
Exit  
Cloakroom

3. Accessibility Navigation

A passenger using a wheelchair can select Accessible Mode.

The system avoids:

Stairs  
Narrow passages  
Inaccessible entrances

and prioritizes:

Lifts  
Ramps  
Accessible paths.

4. Voice Navigation

Visually impaired passengers receive voice instructions for navigation.

For example:

"Move straight for 20 metres and take the lift on your left."

5. Platform Navigation

If the passenger needs to move from Platform 2 to Platform 8, the system provides the appropriate internal route instead of simply showing the station location.

6. AI-Based Route Selection

If multiple routes are available, the system can compare them based on:

Distance  
Estimated walking time  
Accessibility  
Crowd level  
Temporary restrictions

and generate an appropriate route.

7. Digital Kiosk

Passengers who do not have the mobile application can use touchscreen kiosks installed inside the station.

They can select:

Current Location → Destination → Route Mode → Start Navigation

8. Emergency Navigation

The system can provide routes towards:

Emergency exits  
Medical facilities  
Railway help desks  
Security offices

during emergency situations.

## Technology Stack

| **Component** | **Technology** |
| --------------------------- | ----------------------------------- |
| **Mobile Application** | React Native / Flutter |
| **Web/Kiosk Interface** | React.js |
| **Frontend** | HTML, CSS, JavaScript |
| **Backend** | Python / FastAPI |
| **AI/ML** | Python, Scikit-learn |
| **Navigation Algorithm** | Dijkstra / A* |
| **Database** | Firebase / PostgreSQL |
| **Indoor Maps** | OpenStreetMap / Custom Station Maps |
| **Location Detection** | QR / Bluetooth Beacon / Wi-Fi |
| **Voice Navigation** | Text-to-Speech |
| **AI Processing** | Python |
| **Real-Time Communication** | Firebase / WebSockets |
| **Deployment** | Firebase / Render / AWS |

## Dependencies

Software Dependencies

Python 3.x  
Node.js  
React.js / React Native  
FastAPI  
Firebase  
PostgreSQL  
OpenStreetMap  
Git & GitHub  
VS Code  
Web browser

Python Libraries

NumPy  
Pandas  
Scikit-learn  
NetworkX  
FastAPI  
Uvicorn

Frontend Dependencies

React  
React Router  
Leaflet  
Axios

Hardware Dependencies

For the prototype:

Laptop/PC  
Android smartphone  
QR codes  
Optional Bluetooth Beacons  
Optional touchscreen display for kiosk prototype

## Benefits

- Helps passengers find railway station facilities easily.
- Reduces confusion in large and unfamiliar railway stations.
- Saves passenger time by providing direct routes.
- Provides accessible routes for passengers with disabilities.
- Supports visually impaired passengers through voice navigation.
- Helps elderly passengers find suitable routes using lifts and ramps.
- Provides navigation through both mobile applications and digital kiosks.
- Helps passengers locate platforms and important facilities quickly.
- Provides real-time information about facility availability and changes.

## Future Scope

- Integration of 3D interactive railway station maps.
- Augmented Reality (AR) based navigation.
- Indoor positioning using Bluetooth and Wi-Fi.
- Real-time crowd density information.
- IoT integration for smart railway station facilities.
- Support for multiple Indian languages.
- Advanced emergency and evacuation navigation.
- Integration with existing railway applications and services.
- AI-based route recommendations based on passenger requirements.

## Conclusion

RailNav AI provides a smart and user-friendly approach to railway station navigation. By combining interactive station maps, route calculation, accessibility options, voice guidance, real-time updates, and digital kiosks, the system can help passengers navigate railway stations more easily.

The proposed solution focuses on reducing confusion, saving time, improving accessibility, and providing a better passenger experience within railway stations.
