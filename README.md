# GreenStay---Eco-Friendly-Accommodation-Booking-Platform

![GreenStay Banner](https://img.shields.io/badge/GreenStay-Eco--Friendly-brightgreen)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-green)

## Live Demo

[View Live Demo](https://your-demo-link.netlify.app) *<!-- Add your demo link here -->*

## Overview

GreenStay is a modern, responsive web platform dedicated to promoting sustainable tourism by connecting environmentally conscious travelers with eco-friendly accommodations. Every booking contributes to reforestation efforts and supports sustainable practices.

![Screenshot_2-3-2026_183616_127 0 0 1](https://github.com/user-attachments/assets/32ef2b9f-cb4e-403a-9112-a865c7ee6b75)

## Features

###  **Core Features**
- **Property Listings**: Browse through curated eco-friendly accommodations
- **Smart Search**: Filter properties by location and dates
- **Booking System**: Seamless reservation process with eco-options
- **Green Impact Tracker**: Real-time statistics on environmental contributions

### **Sustainability Features**
- **Carbon Offset**: Optional $5 carbon offset per booking
- **Tree Planting**: One tree planted for every reservation
- **Eco-Certification**: All properties verified for sustainable practices
- **Green Badges**: Visual indicators for eco-friendly features

### **User Experience**
- **Responsive Design**: Optimized for all devices (mobile, tablet, desktop)
- **Smooth Animations**: Engaging transitions and hover effects
- **Interactive Modal**: User-friendly booking interface
- **Real-time Stats**: Live updates on environmental impact

## Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Styling**: Custom CSS with Flexbox/Grid
- **Animations**: CSS Keyframes
- **Icons**: Emoji-based icon system
- **Fonts**: Google Fonts (Segoe UI, system fonts)

## Project Structure

```
greenstay/
│
├── index.html          # Main HTML file
├── README.md           # Project documentation
├── LICENSE             # MIT License
│
├── assets/             # (Optional) For images and assets
│   ├── images/         # Property images
│   ├── icons/          # Custom icons
│   └── css/            # (Optional) External CSS files
│
└── js/                 # (Optional) External JavaScript
    └── main.js         # Separated JavaScript logic
```

## Getting Started

### Prerequisites
- Any modern web browser (Chrome, Firefox, Safari, Edge)
- Basic text editor for modifications (VS Code, Sublime, etc.)
- Git (for cloning)

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/greenstay.git
```

2. **Navigate to project directory**
```bash
cd greenstay
```

3. **Open the website**
- Double-click `index.html` to open in browser
- Or use Live Server in VS Code for development

### Local Development

```bash
# Using Python (if you want a local server)
python -m http.server 8000

# Using Node.js (with live-server)
npx live-server

# Then open http://localhost:8000
```

## Usage Examples

### Searching for Properties
```javascript
// Properties are filtered based on user input
function searchProperties() {
    const location = document.querySelector('.search-input').value;
    // Filters and displays matching properties
}
```

### Making a Booking
```javascript
// Each booking triggers eco-initiatives
function confirmBooking(event) {
    event.preventDefault();
    // Plants a tree for every booking
    // Tracks carbon offset if selected
}
```

## Customization

### Adding New Properties
Edit the `properties` array in the JavaScript section:

```javascript
const properties = [
    {
        name: "Your Eco Property",
        location: "Location",
        price: 199,
        rating: 4.5,
        image: "tree", // Emoji or image URL
        features: ["Solar", "Organic", "Recycled"],
        description: "Your property description"
    }
    // Add more properties...
];
```

### Modifying Colors
Update the CSS variables in the `<style>` section:

```css
:root {
    --primary-green: #2e7d32;
    --dark-green: #1b5e20;
    --light-green: #e8f5e9;
    --text-color: #2c3e50;
}
```

## Key Highlights

### Environmental Impact
-  **Trees Planted**: Counter for reforestation contributions
-  **Water Saved**: Tracking conservation efforts
-  **Energy Efficient**: Properties using renewable energy
-  **Waste Reduction**: Zero-waste property certification

### User Benefits
-  **Eco-Certified Stays**: Verified sustainable accommodations
-  **Impact Tracking**: See your environmental contribution
-  **Guilt-Free Travel**: Enjoy vacations while helping the planet
-  **Green Rewards**: Loyalty program for frequent eco-travelers

## Responsive Design

| Device | Breakpoint | Features |
|--------|------------|----------|
| Mobile | < 768px | Stacked layout, simplified nav |
| Tablet | 768px - 1024px | Grid adjustments, visible features |
| Desktop | > 1024px | Full layout, hover effects |

## Contributing

We welcome contributions to make GreenStay even better!

### How to Contribute
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Contribution Ideas
- Add more property listings
- Implement actual image gallery
- Create backend integration
- Add user authentication
- Develop payment gateway
- Multi-language support
- Advanced search filters

## License

Distributed under the MIT License. See `LICENSE` file for more information.

## Acknowledgments

- **Icons**: Emoji icons provided by Unicode Consortium
- **Inspiration**: Sustainable tourism initiatives worldwide
- **Community**: Eco-conscious travelers and property owners

## Contact

Om Gedam

GitHub: @itsomg134

Email: omgedam123098@gmail.com

Twitter (X): @omgedam

LinkedIn: Om Gedam

Portfolio: https://ogworks.lovable.app
