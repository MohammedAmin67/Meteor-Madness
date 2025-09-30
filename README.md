# 🌌 Meteor Madness

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![React](https://img.shields.io/badge/React-18.x-61dafb?logo=react)](https://reactjs.org/)
[![Vite](https://img.shields.io/badge/Vite-5.x-646cff?logo=vite)](https://vitejs.dev/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![GitHub issues](https://img.shields.io/github/issues/yourusername/meteor-madness)](https://github.com/yourusername/meteor-madness/issues)
[![GitHub stars](https://img.shields.io/github/stars/yourusername/meteor-madness)](https://github.com/yourusername/meteor-madness/stargazers)

> **An interactive asteroid impact simulator and planetary defense game**  
> Experience scientifically accurate orbital mechanics, visualize devastating impacts, and explore strategies to defend Earth from cosmic threats.

[Live Demo](https://meteor-madness.demo) • [Report Bug](https://github.com/yourusername/meteor-madness/issues) • [Request Feature](https://github.com/yourusername/meteor-madness/issues)

![Meteor Madness Screenshot](docs/images/screenshot.png)

---

## 📋 Table of Contents

- [Features](#-features)
- [Demo](#-demo)
- [Installation](#-installation)
- [Usage](#-usage)
- [Project Structure](#-project-structure)
- [Technologies](#-technologies)
- [Scripts](#-scripts)
- [Configuration](#-configuration)
- [Contributing](#-contributing)
- [Roadmap](#-roadmap)
- [License](#-license)
- [Acknowledgments](#-acknowledgments)

---

## ✨ Features

### Core Functionality
- 🌍 **Real-time orbital simulation** with accurate physics calculations
- 💥 **Impact modeling** with energy, crater size, and damage predictions
- 📊 **Interactive data visualizations** using D3.js
- 🎮 **Game mode** with planetary defense missions
- 🛡️ **Multiple defense strategies**: kinetic impactors, nuclear deflection, gravity tractors

### Technical Highlights
- ⚡ Built with React 18 and Vite for blazing-fast performance
- 🎨 Modern, responsive UI with Tailwind CSS and shadcn/ui
- 🌐 3D visualizations powered by Three.js
- 📱 Fully responsive design for mobile and desktop
- ♿ Accessible components using Radix UI primitives
- 🔬 Scientific accuracy based on NASA data and physics principles

---

## 🎥 Demo

### Live Application
**[Try Meteor Madness →](https://meteor-madness.demo)**

### Screenshots

<table>
  <tr>
    <td><img src="docs/images/simulation.png" alt="Orbital Simulation" /></td>
    <td><img src="docs/images/impact.png" alt="Impact Analysis" /></td>
  </tr>
  <tr>
    <td align="center"><b>Orbital Simulation</b></td>
    <td align="center"><b>Impact Analysis</b></td>
  </tr>
  <tr>
    <td><img src="docs/images/defense.png" alt="Defense Game" /></td>
    <td><img src="docs/images/visualization.png" alt="Data Viz" /></td>
  </tr>
  <tr>
    <td align="center"><b>Defense Mission</b></td>
    <td align="center"><b>Data Visualization</b></td>
  </tr>
</table>

---

## 🚀 Installation

### Prerequisites

- **Node.js** >= 18.0.0
- **npm** >= 9.0.0 or **yarn** >= 1.22.0

### Quick Start

```bash
# Clone the repository
git clone https://github.com/yourusername/meteor-madness.git

# Navigate to project directory
cd meteor-madness

# Install dependencies
npm install

# Start development server
npm run dev
```

The application will be available at `http://localhost:5173`

### Alternative Package Managers

```bash
# Using yarn
yarn install
yarn dev

# Using pnpm
pnpm install
pnpm dev
```

---

## 📖 Usage

### Development Mode

```bash
npm run dev
```

Starts the Vite development server with hot module replacement (HMR).

### Production Build

```bash
npm run build
```

Creates an optimized production build in the `dist/` directory.

### Preview Production Build

```bash
npm run preview
```

Serves the production build locally for testing.

### Linting

```bash
npm run lint
```

Runs ESLint to check code quality and style.

---

## 📁 Project Structure

```
meteor-madness/
├── .github/
│   └── workflows/          # CI/CD workflows
├── public/
│   ├── assets/            # Static assets
│   └── data/              # Asteroid datasets
├── src/
│   ├── components/
│   │   ├── simulation/    # Orbital mechanics components
│   │   ├── visualization/ # D3/Three.js visualizations
│   │   ├── game/          # Defense game components
│   │   └── ui/            # Reusable UI components
│   ├── lib/
│   │   ├── physics/       # Impact calculations
│   │   ├── astronomy/     # Orbital mechanics
│   │   └── utils/         # Helper functions
│   ├── hooks/             # Custom React hooks
│   ├── context/           # React context providers
│   ├── styles/            # Global styles
│   ├── types/             # TypeScript definitions
│   ├── constants/         # App constants
│   ├── App.jsx            # Root component
│   └── main.jsx           # Entry point
├── docs/                  # Documentation
├── tests/                 # Test files
├── .env.example           # Environment variables template
├── .eslintrc.json         # ESLint configuration
├── .gitignore
├── index.html
├── package.json
├── postcss.config.js
├── tailwind.config.js
├── vite.config.js
└── README.md
```

---

## 🛠️ Technologies

### Frontend Framework
- **React** 18.2.0 - UI component library
- **React DOM** 18.2.0 - React rendering

### Build Tools
- **Vite** 5.x - Next generation frontend tooling
- **PostCSS** - CSS transformation
- **Autoprefixer** - CSS vendor prefixing

### Styling
- **Tailwind CSS** 3.x - Utility-first CSS framework
- **shadcn/ui** - Re-usable component library
- **Radix UI** - Accessible component primitives
- **class-variance-authority** - CSS utility for variants
- **clsx** - Utility for constructing className strings
- **tailwind-merge** - Merge Tailwind classes

### Visualization
- **D3.js** 7.x - Data visualization library
- **Three.js** - 3D graphics library
- **@react-three/fiber** - React renderer for Three.js
- **@react-three/drei** - Useful helpers for react-three-fiber

### UI Components & Icons
- **Lucide React** - Beautiful icon library
- **Framer Motion** - Animation library

### Utilities
- **date-fns** - Date manipulation
- **recharts** - Composable charting library

---

## 📜 Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server on port 5173 |
| `npm run build` | Build for production |
| `npm run preview` | Preview production build locally |
| `npm run lint` | Run ESLint |
| `npm run lint:fix` | Fix ESLint errors automatically |
| `npm run format` | Format code with Prettier |
| `npm run test` | Run test suite |
| `npm run test:watch` | Run tests in watch mode |
| `npm run type-check` | Check TypeScript types |

---

## ⚙️ Configuration

### Environment Variables

Create a `.env` file in the root directory:

```env
# API Configuration
VITE_API_BASE_URL=https://api.meteormadness.com
VITE_NASA_API_KEY=your_nasa_api_key_here

# Feature Flags
VITE_ENABLE_ANALYTICS=true
VITE_ENABLE_3D_RENDERING=true

# Development
VITE_DEBUG_MODE=false
```

### Tailwind Configuration

Customize the theme in `tailwind.config.js`:

```js
export default {
  content: ['./index.html', './src/**/*.{js,jsx}'],
  theme: {
    extend: {
      colors: {
        // Add custom colors
      },
    },
  },
  plugins: [],
}
```

### Vite Configuration

Modify build settings in `vite.config.js`:

```js
export default defineConfig({
  plugins: [react()],
  server: {
    port: 5173,
  },
  build: {
    outDir: 'dist',
  },
})
```

---

## 🤝 Contributing

We welcome contributions from the community! Here's how you can help:

### Getting Started

1. **Fork the repository**
2. **Clone your fork**
   ```bash
   git clone https://github.com/your-username/meteor-madness.git
   ```
3. **Create a feature branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```
4. **Make your changes**
5. **Commit with conventional commits**
   ```bash
   git commit -m "feat: add amazing feature"
   ```
6. **Push to your fork**
   ```bash
   git push origin feature/amazing-feature
   ```
7. **Open a Pull Request**

### Commit Convention

We follow [Conventional Commits](https://www.conventionalcommits.org/):

- `feat:` New features
- `fix:` Bug fixes
- `docs:` Documentation changes
- `style:` Code style changes (formatting, etc.)
- `refactor:` Code refactoring
- `test:` Test updates
- `chore:` Maintenance tasks

### Code Style

- Run `npm run lint` before committing
- Follow the existing code style
- Write clear, descriptive variable names
- Add comments for complex logic
- Keep functions small and focused

### Pull Request Guidelines

- Update documentation for new features
- Add tests for bug fixes and new features
- Ensure all tests pass
- Keep PRs focused on a single concern
- Reference related issues in PR description

---

## 🗺️ Roadmap

### Version 1.0 (Current)
- [x] Basic orbital simulation
- [x] Impact calculations
- [x] 3D visualization
- [x] Defense game mode
- [x] Responsive design

### Version 1.1 (In Progress)
- [ ] Real-time NASA NEO data integration
- [ ] Historical impact event database
- [ ] Multiplayer defense missions
- [ ] Advanced physics models
- [ ] Mobile app (React Native)

### Version 2.0 (Planned)
- [ ] VR/AR support
- [ ] Machine learning threat prediction
- [ ] Community scenario sharing
- [ ] Educational curriculum integration
- [ ] API for developers

### Long-term Vision
- [ ] Integration with telescope networks
- [ ] Citizen science contributions
- [ ] Academic research partnerships
- [ ] International space agency collaboration

See the [open issues](https://github.com/yourusername/meteor-madness/issues) for a full list of proposed features and known issues.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2025 Meteor Madness Contributors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction...
```

---

## 🙏 Acknowledgments

### Data Sources
- [NASA Center for Near-Earth Object Studies (CNEOS)](https://cneos.jpl.nasa.gov/) - NEO data
- [Minor Planet Center](https://www.minorplanetcenter.net/) - Asteroid orbital elements
- [JPL Small-Body Database](https://ssd.jpl.nasa.gov/sbdb.cgi) - Physical characteristics

### Inspiration
- NASA's [DART Mission](https://www.nasa.gov/dart) - First planetary defense test
- ESA's [Hera Mission](https://www.esa.int/Safety_Security/Hera) - Follow-up assessment
- [The Planetary Society](https://www.planetary.org/) - Planetary defense advocacy

### Libraries & Tools
- [Three.js](https://threejs.org/) - 3D graphics
- [D3.js](https://d3js.org/) - Data visualization
- [shadcn/ui](https://ui.shadcn.com/) - Component library
- [Tailwind CSS](https://tailwindcss.com/) - Styling framework

### Community
Special thanks to all [contributors](https://github.com/yourusername/meteor-madness/graphs/contributors) who have helped improve this project!

---

## 📞 Support & Contact

- **Documentation**: [docs.meteormadness.com](https://docs.meteormadness.com)
- **Bug Reports**: [GitHub Issues](https://github.com/yourusername/meteor-madness/issues)
- **Feature Requests**: [GitHub Discussions](https://github.com/yourusername/meteor-madness/discussions)
- **Email**: hello@meteormadness.com
- **Discord**: [Join our community](https://discord.gg/meteor-madness)
- **Twitter**: [@MeteorMadnessApp](https://twitter.com/MeteorMadnessApp)

---

## 📊 Project Stats

![GitHub repo size](https://img.shields.io/github/repo-size/yourusername/meteor-madness)
![GitHub language count](https://img.shields.io/github/languages/count/yourusername/meteor-madness)
![GitHub top language](https://img.shields.io/github/languages/top/yourusername/meteor-madness)
![GitHub last commit](https://img.shields.io/github/last-commit/yourusername/meteor-madness)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/yourusername/meteor-madness)

---

<div align="center">

**[⬆ Back to Top](#-meteor-madness)**

Made with ❤️ and ☕ by space enthusiasts

⭐ **Star us on GitHub — it helps!**

</div>