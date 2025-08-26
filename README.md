# SimpleSky - Professional Astrophotography Planning

![SimpleSky Logo](https://simplesky.app/images/simple-sky-logo-240.png)

**Version 1.0.2** | [Live App](https://simplesky.app) | [Author: Joshua Walderbach](https://github.com/8bits1beard)

## Overview

SimpleSky is a professional-grade web application designed to streamline astrophotography planning by combining real-time weather data, celestial object recommendations, and telescope compatibility analysis. Built for both amateur and experienced astrophotographers, SimpleSky takes the guesswork out of planning your next imaging session.

## Key Features

### 🌌 Comprehensive Celestial Database
- **696+ Deep Sky Objects**: Complete Messier, NGC, and IC catalogs
- **Smart Recommendations**: AI-powered object suggestions based on your equipment, location, and current conditions
- **Detailed Object Information**: Physical properties, imaging difficulty scores, and optimal viewing times
- **High-Resolution Imagery**: Professional astrophotography images for reference

### 🔭 Telescope Management
- **41 Pre-configured Models**: Popular telescopes from Celestron, Meade, Sky-Watcher, and more
- **Custom Equipment Support**: Add your own telescope specifications
- **Compatibility Scoring**: Real-time analysis of object-telescope compatibility
- **Field of View Calculations**: Precise FOV calculations for imaging planning

### 🌤️ Advanced Weather Integration
- **Real-Time Conditions**: Current temperature, humidity, cloud cover, and seeing conditions
- **Multi-Day Forecasts**: Plan sessions up to 7 days in advance
- **Astronomy-Specific Metrics**: Moon phase, astronomical twilight, and transparency ratings
- **Multiple Weather Providers**: Redundant data sources for reliability

### 📍 Location Services
- **GPS Auto-Detection**: Automatic location detection with manual override
- **Dark Sky Site Database**: Curated list of premier observation locations
- **Astronomy Club Directory**: Connect with local astronomy communities
- **Bortle Scale Integration**: Light pollution assessment for your location

### 📊 Intelligent Scoring System
- **Astrophotography Score**: Combines weather, object visibility, and equipment compatibility
- **Weather Score**: Weighted analysis of cloud cover, humidity, temperature, and wind
- **Object Score**: Factors in altitude, magnitude, size, and imaging difficulty
- **Session Planning**: Hour-by-hour scoring for optimal timing

## Technical Specifications

### Frontend
- **Framework**: Vanilla JavaScript ES6+ with modular architecture
- **UI**: Responsive design optimized for tablets and desktop
- **Performance**: Lazy loading, code splitting, and optimized asset delivery
- **PWA**: Progressive Web App with offline capabilities

### Data Management
- **Caching**: Intelligent caching system for offline functionality
- **Storage**: IndexedDB for large datasets, localStorage for settings
- **Updates**: Automatic data synchronization when online

### API Integrations
- **Weather**: OpenWeather API, NOAA/NWS, Open-Meteo
- **Astronomy**: Custom astronomy calculations, ephemeris data
- **Geolocation**: Browser Geolocation API, IP-based fallback

## Browser Support

- Chrome 90+ (Recommended)
- Firefox 88+
- Safari 14+
- Edge 90+

## Installation

SimpleSky is a web application that runs directly in your browser. No installation required!

1. Visit [simplesky.app](https://simplesky.app)
2. Allow location access for automatic setup
3. Select your telescope or add custom equipment
4. Start planning your astrophotography sessions

### Progressive Web App (PWA)

For offline access and app-like experience:
- **Mobile**: Tap "Add to Home Screen" in your browser menu
- **Desktop**: Click the install icon in the address bar

## Usage Guide

### Quick Start
1. **Set Location**: Allow GPS or manually enter coordinates
2. **Configure Telescope**: Select from presets or add custom specs
3. **View Recommendations**: Browse tonight's best targets
4. **Check Weather**: Review conditions and scoring
5. **Plan Session**: Use hourly forecasts to optimize timing

### Advanced Features
- **Filters**: Sort objects by type, constellation, or difficulty
- **Search**: Find specific objects by name or catalog number
- **Export**: Save session plans and object lists
- **Customization**: Adjust scoring weights and preferences

## Privacy & Security

- **No Account Required**: Use anonymously without registration
- **Local Storage**: Your data stays on your device
- **Secure APIs**: All external connections use HTTPS
- **No Tracking**: No analytics or user tracking implemented

## Development

### Tech Stack
- HTML5, CSS3, JavaScript (ES6+)
- Service Workers for offline functionality
- IndexedDB for data persistence
- Leaflet.js for mapping
- Python for data pipeline and catalog building

## Contributing

While SimpleSky is currently maintained as a personal project, feedback and suggestions are welcome! Please open an issue on GitHub for:
- Bug reports
- Feature requests
- Documentation improvements
- General feedback

## License

MIT License - See [LICENSE](LICENSE) file for details

## Acknowledgments

- Astronomical data from SIMBAD, VizieR, and OpenNGC
- Weather data from OpenWeather, NOAA, and Open-Meteo
- Astrophotography images from the astronomy community
- Built with passion for the astronomy community

## Support

- **Documentation**: [GitHub Wiki](https://github.com/yourusername/SimpleSky/wiki)
- **Issues**: [GitHub Issues](https://github.com/yourusername/SimpleSky/issues)

---

**SimpleSky - Making Astrophotography Simple**

*Clear skies and happy imaging!* 🌟🔭📸