
# MobileMonero Setup Guide

**MobileMonero** is a step-by-step guide application that helps users set up MobileMonero on their Android devices using Termux. This web application provides an easy-to-follow tutorial for joining the MobileMonero network, which is part of the XMRT ecosystem.

## About MobileMonero

MobileMonero brings privacy-focused cryptocurrency functionality to mobile devices, leveraging the power of Monero's technology with enhanced mobile optimization. It's designed to make cryptocurrency accessible to everyone, anywhere.

## Features

- **Multi-language Support**: Available in English and Spanish
- **Step-by-step Guide**: Clear, numbered instructions for setup
- **Copy-to-clipboard**: Easy command copying for terminal use
- **Mobile-optimized**: Designed specifically for mobile devices
- **Progress Tracking**: Visual step indicator to track progress

## Setup Process

The app guides users through three main steps:

1. **Install Termux** - Get the terminal emulator from Google Play Store
2. **Install Python** - Set up Python environment in Termux
3. **Join MobileMonero** - Run the signup script to join the network

## Technology Stack

- **React** with TypeScript
- **Vite** for build tooling
- **Tailwind CSS** for styling
- **Framer Motion** for animations
- **Shadcn/ui** components
- **React Router** for navigation

## Getting Started

### Prerequisites

- Node.js (version 18 or higher)
- npm or yarn package manager

### Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```

### Building for Production

```bash
npm run build
```

## Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── ui/             # Shadcn/ui components
│   ├── StepCard.tsx    # Individual step display
│   └── StepIndicator.tsx # Progress indicator
├── pages/
│   └── Index.tsx       # Main application page
├── hooks/              # Custom React hooks
└── lib/                # Utility functions
```

## Contributing

This project is part of the XMRT ecosystem. For contributions or issues, please contact the development team.

## Support

For technical support or questions:
- Email: xmrtsolutions@gmail.com
- Website: https://xmrt.io/

## License

This project is part of the XMRT ecosystem and follows the project's licensing terms.

## About XMRT

XMRT is focused on bringing privacy-focused cryptocurrency solutions to mobile platforms, making decentralized finance accessible to everyone worldwide.
