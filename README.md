# FarmAiEcom
#  Mobile App

## 📽 Demo

▶️ [Watch Demo Video](https://drive.google.com/file/d/1IrVlmvNAxi8beF0-jue8-eVpOicnV9nh/view?usp=sharing)

📥 [Download APK](https://drive.google.com/file/d/15xxK29fRWqaGmjYZRDXiq-TkjQy5pRvQ/view?usp=sharing)

A comprehensive React Native mobile application for agricultural technology solutions, featuring AI-powered farming assistance, e-commerce capabilities, and educational resources.

## 🌟 Features

- **AI Farming Services**
  - Weather Monitoring
  - Soil Health Analysis
  - Precision Irrigation
  - Crop Monitoring
  - Pest & Disease Management
  - Agro-economy Services

- **E-commerce Platform**
  - Product Catalog
  - Shopping Cart
  - Order Management
  - Secure Checkout

- **Educational Resources**
  - Online Courses
  - Video Tutorials
  - Success Stories
  - Certification System

- **User Management**
  - Multi-language Support (English, Hindi, Marathi)
  - Profile Management
  - Farm & Crop Management
  - Push Notifications

## 🏗 Architecture Overview

### Core Technologies
- React Native
- Redux Toolkit
- Firebase Services
- i18next (Internationalization)

### Directory Structure
```
src/
├── assets/          # Images, fonts, and other static assets
├── components/      # Reusable UI components
├── screens/         # Application screens/pages
├── navigation/      # Navigation configuration
├── store/          # Redux store setup
│   ├── actions/    # Redux actions
│   └── reducers/   # Redux reducers
├── services/       # API and third-party service integrations
├── utils/          # Utility functions and helpers
├── translation/    # Internationalization files
├── validation/     # Form validation schemas
└── shared/         # Shared components and utilities
```

### Key Components

1. **State Management**
   - Redux Toolkit for global state
   - Async storage for local persistence
   - Custom reducers for specific features

2. **Navigation**
   - Stack Navigator for main navigation
   - Bottom Tab Navigator for main sections
   - Drawer Navigator for additional options

3. **API Integration**
   - Axios for HTTP requests
   - Custom interceptors for authentication
   - Error handling middleware

4. **Authentication**
   - Firebase Authentication
   - JWT token management
   - Secure storage implementation

## 🚀 Getting Started

### Prerequisites
- Node.js >= 18
- React Native CLI
- Android Studio/Xcode

### Installation

1. Clone the repository:
```bash
git clone [repository-url]
```

2. Install dependencies:
```bash
npm install
```

3. Set up environment variables:
```bash
cp .env.example .env
```

4. Start the development server:
```bash
npm start
```

5. Run on Android/iOS:
```bash
npm run android
# or
npm run ios
```

### Environment Setup

Create a `.env` file with the following configurations:
```env
API_URL=your_api_url
MAP_URL=your_mapbox_url
STYLE_URL=your_mapbox_style
APP_FIREBASE_API_KEY=your_firebase_key
# Add other required environment variables
```

## 📱 Core Features Implementation

### AI Services Integration
- Weather API integration
- ML models for crop analysis
- Real-time monitoring systems

### E-commerce Flow
- Product management
- Cart functionality
- Order processing
- Payment integration

### Educational Platform
- Course management
- Progress tracking
- Certificate generation
- Video content delivery

## 🔒 Security Features

- API request encryption
- Secure token management
- Environment variable protection
- Firebase security rules

## 🌐 Internationalization

Supports multiple languages through i18next:
- English (default)
- Hindi
- Marathi

## 📦 State Management

Redux store structure:
- Authentication state
- User profile
- Shopping cart
- Course progress
- Notifications

## 🔄 CI/CD Integration

- SonarQube for code quality
- Jest for testing
- ESLint for code style
- Automated deployment workflows

## 📝 Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## 🤝 Support
https://mriyan.in
