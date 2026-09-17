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
