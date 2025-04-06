# 🚚 Transport Co. Delivery Dashboard


## 📋 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Map Integration](#map-integration)
- [Responsive Design](#responsive-design)
- [Browser Support](#browser-support)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## 🌟 Overview

The Transport Co. Delivery Dashboard is a modern, responsive web application designed to provide end customers with real-time tracking and management of their deliveries. The dashboard offers a sleek dark-themed interface with interactive elements, live map tracking, and comprehensive delivery information.

## ✨ Features

- **📱 Responsive Design**: Fully responsive layout that works on mobile, tablet, and desktop devices
- **🗺️ Live Map Tracking**: Real-time visualization of delivery routes using OpenStreetMap
- **📦 Active Shipment Tracking**: Detailed information about current deliveries
- **📅 Upcoming Deliveries**: Preview of scheduled deliveries
- **📜 Delivery History**: Complete record of past deliveries
- **🌙 Dark Mode**: Modern dark theme for reduced eye strain
- **🔔 Notifications**: Real-time status updates and alerts
- **👤 User Profile**: Personalized user experience
- **📊 Interactive Elements**: Hover effects, animations, and transitions
- **🔍 Search & Filter**: Easy navigation through delivery information

## 🛠️ Technologies Used

- **HTML5**: Semantic markup for structure
- **Tailwind CSS**: Utility-first CSS framework for styling
- **JavaScript**: Interactive functionality
- **Leaflet.js**: Open-source JavaScript library for interactive maps
- **OpenStreetMap**: Free, editable map of the world
- **Lucide Icons**: Beautiful, consistent icons
- **Inter Font**: Modern, clean typography
- **CSS Animations**: Smooth transitions and effects

## 🚀 Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/transport-delivery-dashboard.git
   cd transport-delivery-dashboard
   ```

2. **Open the project**:
   - Simply open the `index.html` file in your browser
   - No build process required as we're using CDN links

3. **For local development**:
   - Use a local server (like Live Server in VS Code)
   - This ensures proper loading of external resources

## 💻 Usage

1. **View Active Shipments**:
   - The dashboard automatically displays your current delivery
   - Track the driver's location on the interactive map
   - View estimated arrival time and delivery progress

2. **Check Upcoming Deliveries**:
   - See all scheduled deliveries in the upcoming section
   - View delivery details, tracking IDs, and expected arrival times

3. **Access Delivery History**:
   - Browse through past deliveries in the history table
   - Click "View Details" for more information about specific deliveries

4. **Interact with the Map**:
   - Zoom in/out to see more details
   - Click on markers to view location information
   - Track the delivery route in real-time

## 🎨 Customization

### Changing Colors

The dashboard uses CSS variables for easy customization. Edit the following in the `<style>` section:

```css
:root {
    --primary: #6366F1;      /* Primary color */
    --primary-dark: #4F46E5; /* Darker shade of primary */
    --secondary: #10B981;    /* Secondary color */
    --accent: #F59E0B;       /* Accent color */
}
```

### Modifying Map Settings

To change the default map location or styling:

```javascript
// Change default location (latitude, longitude, zoom level)
const map = L.map('delivery-map').setView([40.7128, -74.0060], 13);

// Customize route line appearance
const routeLine = L.polyline([
    [40.7028, -74.0160], // Driver location
    [40.7078, -74.0110], // Intermediate point
    [40.7128, -74.0060]  // Destination
], {
    color: '#6366F1',    // Line color
    weight: 3,            // Line width
    opacity: 0.7,         // Line opacity
    dashArray: '10, 10'   // Line style (dashed)
}).addTo(map);
```

## 🗺️ Map Integration

The dashboard uses OpenStreetMap with Leaflet.js for map functionality:

- **Free to Use**: OpenStreetMap is free and doesn't require an API key
- **Custom Styling**: Dark theme styling for the map to match the dashboard
- **Interactive Elements**: Markers, polylines, and animated elements
- **Responsive**: Works on all device sizes

To use a different map provider:
1. Replace the tile layer URL in the JavaScript section
2. Update the attribution information
3. Adjust styling as needed

## 📱 Responsive Design

The dashboard is built with a mobile-first approach:

- **Mobile**: Single column layout with optimized spacing
- **Tablet**: Two-column layout for upcoming deliveries
- **Desktop**: Full layout with all features visible
- **Adaptive Components**: Elements resize and reposition based on screen size

## 🌐 Browser Support

The dashboard is compatible with:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Android Chrome)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 📞 Contact

Transport Co. - [support@transportco.com](mailto:support@transportco.com)

Project Link: [https://github.com/yourusername/transport-delivery-dashboard](https://github.com/yourusername/transport-delivery-dashboard)

---

Made with ❤️ by Transport Co. Team 
