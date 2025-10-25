# Prakriti Pulse - Your Inner Balance Guide

A comprehensive wellness platform that bridges ancient Ayurvedic wisdom with modern health needs, helping users discover their unique body constitution (Prakriti) and achieve holistic well-being.

## Description

Prakriti Pulse is a hybrid web application that combines traditional HTML/CSS/JavaScript pages with a modern React + TypeScript frontend. The platform offers:

- **Ayurveda & Yoga Education**: Learn about the ancient science of life, three doshas, and traditional yoga practices
- **Dosha Assessment**: Comprehensive Prakriti quiz to discover your unique body constitution
- **Nutrition Guide**: Personalized dietary recommendations based on your dosha type
- **Mind Wellness**: Traditional Indian approaches to mental health and emotional balance
- **Blog**: Educational content about holistic wellness

The application is built with modern web technologies including React, TypeScript, Vite, and Tailwind CSS, while maintaining the traditional wisdom and cultural authenticity of Ayurvedic practices.

## Features

- 🧘 **Dosha Quiz**: Interactive assessment to determine your Prakriti type
- 🌿 **Ayurveda Education**: Comprehensive information about Ayurvedic principles
- 🥗 **Nutrition Guidance**: Personalized dietary recommendations
- 🧠 **Mental Wellness**: Traditional approaches to mind-body balance
- 📱 **Responsive Design**: Works seamlessly across all devices
- ⚡ **Modern Tech Stack**: Built with React, TypeScript, and Vite for optimal performance

## Installation Steps

### Prerequisites

- **Node.js** (version 16.0 or higher)
- **npm** (comes with Node.js) or **yarn**

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd IHWP/project
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```
   
   Or if you prefer yarn:
   ```bash
   yarn install
   ```

3. **Verify installation**
   ```bash
   npm run lint
   ```

## How to Run the Project

### Development Mode

To start the development server with hot reload:

```bash
npm run dev
```

The application will be available at `http://localhost:5173` (or the next available port).

### Production Build

To create a production build:

```bash
npm run build
```

The built files will be generated in the `dist/` directory.

### Preview Production Build

To preview the production build locally:

```bash
npm run preview
```

### Linting

To check code quality and style:

```bash
npm run lint
```

## Project Structure

```
project/
├── src/                    # React + TypeScript application
│   ├── App.tsx            # Main React component
│   ├── main.tsx           # Application entry point
│   ├── index.css          # Global styles
│   └── vite-env.d.ts      # Vite type definitions
├── *.html                 # Traditional HTML pages
│   ├── index.html         # Main landing page
│   ├── ayurveda.html      # Ayurveda education page
│   ├── quiz.html          # Dosha assessment quiz
│   ├── nutrition.html     # Nutrition guidance
│   ├── mental-health.html # Mental wellness content
│   └── blog.html          # Blog page
├── *.js                   # JavaScript functionality
├── styles.css             # Global CSS styles
├── package.json           # Dependencies and scripts
├── vite.config.ts         # Vite configuration
├── tailwind.config.js     # Tailwind CSS configuration
└── tsconfig.json          # TypeScript configuration
```

## Technologies Used

### Frontend Framework
- **React 18.3.1** - Modern UI library
- **TypeScript 5.5.3** - Type-safe JavaScript
- **Vite 5.4.2** - Fast build tool and dev server

### Styling
- **Tailwind CSS 3.4.1** - Utility-first CSS framework
- **PostCSS 8.4.35** - CSS processing
- **Autoprefixer 10.4.18** - CSS vendor prefixing

### Development Tools
- **ESLint 9.9.1** - Code linting
- **Lucide React 0.344.0** - Icon library

### Traditional Web
- **HTML5** - Semantic markup
- **CSS3** - Custom styling
- **Vanilla JavaScript** - Interactive functionality

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Support

For support, email support@prakritipulse.com or create an issue in the repository.

---

**Prakriti Pulse** - Bridging ancient wisdom with modern wellness needs 🌿✨
