# The Chat Game

A modern and engaging chat-based game that brings people together through interactive conversations.

## Description

The Chat Game is an innovative platform that transforms regular chat interactions into an engaging gaming experience. Players can participate in various chat-based challenges, compete with friends, and enjoy a unique social gaming experience.

## Features

- Real-time chat interactions
- Multiple game modes
- User-friendly interface
- Social features and friend system
- Score tracking and leaderboards

## Technology Stack

### Backend (API)
- **.NET Core**: Modern, cross-platform framework for building web APIs
- **PostgreSQL Server**: Primary database

### Mobile App
- **React Native**: Cross-platform mobile development
- **Expo**: Development platform and tools
- **TypeScript**: Type-safe JavaScript
- **React Navigation**: Navigation library

## Architecture

The project follows a microservices architecture with three main components:

1. **API Service** (`/api`)
   - Handles all backend operations
   - Processes game logic
   - Handles real-time communication

2. **Mobile App** (`/app`)
   - Cross-platform mobile client
   - User interface and interactions
   - Local state management
   - Real-time updates