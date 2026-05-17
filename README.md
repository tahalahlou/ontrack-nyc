# OnTrack NYC

Real-time NYC Subway tracking app covering all 26 routes and 900+ stops. 
Built with React and TypeScript, deployed via Docker and Nginx.

## What I Built

- Real-time train arrival interface with 5-second live polling across 23 subway lines and 3 shuttles
- Visibility-aware polling — suspends background requests when tab is unfocused to reduce server load
- 2-stage Docker build: Node compile → Nginx runtime with 1-year static asset cache TTL
- 4-stage CI/CD pipeline via GitHub Actions with automated versioned releases to Docker Hub

## Stack
TypeScript, React, Docker, Nginx, REST APIs

## Run Locally

```bash
npm start
```

## Data
NYC subway data served via [Transiter](https://github.com/jamespfennell/transiter)
