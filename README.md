# Restoflow Restaurant Ops App

Restaurant operations system for service teams: mobile workflow, real-time order processing, and TV kitchen display.

## Overview

This repository is a showcase of a production restaurant app delivered for a real business workflow.

The system includes:
- Mobile roles: waiter, kitchen, admin, director
- Backend API for auth, menu, orders, and analytics
- Realtime events via WebSocket / Socket.IO
- TV display for live kitchen queue updates

## Demo Block

### Mobile Demo (9:16)

<p align="center">
  <video src="./docs/restoflow.mp4" width="320" controls playsinline preload="metadata"></video>
</p>

<p align="center">
  If the player is not shown in your browser, open the file directly:
  <a href="./docs/restoflow.mp4">restoflow.mp4</a>
</p>

### TV Display

<p align="center">
  <img src="./docs/tvdisplay.png" alt="Restoflow TV display screen" width="880" />
</p>

## Key Flows

- Waiter creates and updates orders from mobile
- Kitchen receives new orders in real time
- Order statuses are synced instantly across all clients
- TV display auto-refreshes queue state for kitchen visibility

## Tech Stack

- Frontend Mobile: React Native, Redux
- Backend: Node.js, Express
- Realtime: Socket.IO / WebSocket
- Database: PostgreSQL
- Cache / Queue support: Redis
- Deployment: Docker, Nginx

## Notes

- This repository is a showcase version (media + project description).
- Source code is not published due to commercial delivery constraints.
