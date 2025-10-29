# Fullstack Recipe Finder

![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![React](https://img.shields.io/badge/react-18.x-blue)
![License](https://img.shields.io/badge/license-MIT-green)

## Project Overview
Fullstack Recipe Finder is a comprehensive food discovery platform that helps users find recipes based on available ingredients, plan meals, track nutrition, and share culinary creations with a community of food enthusiasts.

## Tech Stack
- **Frontend**: React.js, Next.js, Tailwind CSS
- **Backend**: Node.js, Express.js, GraphQL
- **Database**: MongoDB, Elasticsearch
- **APIs**: Spoonacular API, Edamam Nutrition API
- **Image Storage**: Cloudinary
- **Authentication**: Auth0, JWT
- **Testing**: Jest, Cypress, Mocha

## Features
- ✅ Ingredient-based recipe search
- ✅ Advanced filtering (diet, cuisine, allergies)
- ✅ Nutritional information display
- ✅ Meal planning calendar
- ✅ Shopping list generator
- ✅ Recipe rating and reviews
- ✅ User recipe contributions
- ✅ Step-by-step cooking mode
- ✅ Voice-guided instructions
- ✅ Recipe scaling
- ✅ Favorite recipes collection
- ✅ Social sharing features

## Setup Instructions

### Prerequisites
- Node.js 16.x or higher
- MongoDB
- Elasticsearch (optional)

### Installation

```bash
# Clone the repository
git clone https://github.com/shithel9360/fullstack-recipe-finder.git
cd fullstack-recipe-finder

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env
# Add your API keys (Spoonacular, Edamam, Cloudinary, Auth0)

# Run database setup
npm run db:setup

# Start development server
npm run dev

# For production build
npm run build
npm start
```

### Running Tests

```bash
# Run all tests
npm test

# Run unit tests
npm run test:unit

# Run E2E tests
npm run test:e2e

# Run with coverage
npm run test:coverage
```

## Demo

![Demo GIF Placeholder](https://via.placeholder.com/800x400.png?text=Recipe+Finder+Demo)

## API Documentation

API documentation available at `/graphql` (GraphQL Playground)

## Contributing

Contributions are welcome! Please read CONTRIBUTING.md.

## License

MIT License - see LICENSE file for details

## Contact

Shithel - [@shithel9360](https://github.com/shithel9360)
