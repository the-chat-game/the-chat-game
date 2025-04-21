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
- **Entity Framework Core**: ORM for database operations
- **SignalR**: Real-time communication library
- **SQL Server**: Primary database
- **JWT Authentication**: Secure user authentication
- **Swagger**: API documentation and testing

### Mobile App
- **React Native**: Cross-platform mobile development
- **Expo**: Development platform and tools
- **TypeScript**: Type-safe JavaScript
- **React Navigation**: Navigation library
- **React Native Paper**: Material Design components
- **React Query**: Data fetching and caching
- **Zustand**: State management
- **Expo EAS**: Build and deployment system

### Development Tools
- **Git**: Version control
- **GitHub Actions**: CI/CD pipeline
- **Docker**: Containerization
- **VS Code**: Recommended IDE
- **Postman**: API testing
- **ESLint & Prettier**: Code formatting and linting

## Architecture

The project follows a microservices architecture with three main components:

1. **API Service** (`/api`)
   - Handles all backend operations
   - Manages user authentication
   - Processes game logic
   - Handles real-time communication

2. **Mobile App** (`/app`)
   - Cross-platform mobile client
   - User interface and interactions
   - Local state management
   - Real-time updates

3. **Internal Packages** (`/internal`)
   - Shared libraries and utilities
   - Common data models
   - Cross-cutting concerns

## Development Environment

### Prerequisites
- Node.js (v16 or higher)
- .NET Core SDK
- SQL Server
- Docker (optional)
- iOS Simulator / Android Studio (for mobile development)

### Getting Started

1. Clone the repository:
```bash
git clone https://github.com/yourusername/the-chat-game.git
cd the-chat-game
```

2. Set up the API:
```bash
cd api
dotnet restore
dotnet run
```

3. Set up the mobile app:
```bash
cd app
npm install
npm start
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

Your Name - [@yourtwitter](https://twitter.com/yourtwitter)

Project Link: [https://github.com/yourusername/the-chat-game](https://github.com/yourusername/the-chat-game)