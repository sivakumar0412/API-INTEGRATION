# API-INTEGRATION 

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: D SIVA KUMAR

*INTERN ID*: CT06DH1140

*DOMAIN*: Full Stack Web Development

*DURATION*: 6 WEEEKS

*MENTOR*:NEELA SANTOSH

# API Integration Dashboard

A modern, responsive web application that demonstrates dynamic API integration by fetching and displaying real-time data from multiple public APIs including weather and news services.

## 🌟 Features

- **Real-time Weather Data**: Displays current weather conditions, temperature, humidity, and wind information
- **Latest News Feed**: Shows top news articles with titles, descriptions, and publication details
- **Responsive Design**: Optimized for all screen sizes from mobile to desktop
- **Modern UI/UX**: Features glassmorphism design, smooth animations, and interactive elements
- **Auto-refresh**: Automatically updates data every 10 minutes
- **Error Handling**: Graceful fallback with mock data when APIs are unavailable
- **Loading States**: Visual feedback during data fetching

## 🚀 Demo

The application fetches data from:
- **Weather API**: OpenWeatherMap API for current weather conditions
- **News API**: NewsAPI for latest news articles

*Note: Demo includes fallback mock data to ensure functionality even when external APIs are unavailable.*

## 🛠️ Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with flexbox, grid, and animations
- **Vanilla JavaScript**: ES6+ features including async/await and fetch API
- **Responsive Design**: Mobile-first approach with CSS Grid and Flexbox
- **Modern UI Elements**: Glassmorphism, gradients, and micro-interactions

## 📋 Prerequisites

- Modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection for API calls
- Basic understanding of HTML, CSS, and JavaScript (for customization)

## 🔧 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/api-integration-dashboard.git
   ```

2. Navigate to the project directory:
   ```bash
   cd api-integration-dashboard
   ```

3. Open `index.html` in your web browser or serve it using a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx http-server
   
   # Using VS Code Live Server extension
   Right-click on index.html → "Open with Live Server"
   ```

## 🔑 API Configuration

To use live APIs instead of mock data:

### Weather API (OpenWeatherMap)
1. Sign up at [OpenWeatherMap](https://openweathermap.org/api)
2. Get your free API key
3. Replace `demo` in the weather fetch URL with your API key:
   ```javascript
   const response = await fetch('https://api.openweathermap.org/data/2.5/weather?q=London&appid=YOUR_API_KEY&units=metric');
   ```

### News API
1. Sign up at [NewsAPI](https://newsapi.org/)
2. Get your free API key
3. Replace `demo` in the news fetch URL with your API key:
   ```javascript
   const response = await fetch('https://newsapi.org/v2/top-headlines?country=us&apiKey=YOUR_API_KEY');
   ```

## 📱 Responsive Design

The dashboard is fully responsive and adapts to different screen sizes:

- **Desktop**: Full grid layout with side-by-side cards
- **Tablet**: Responsive grid that adjusts to screen width
- **Mobile**: Single-column layout with optimized touch interactions

## 🎨 Customization

### Styling
- Modify CSS variables in the `<style>` section for colors and spacing
- Update gradient backgrounds and card styles
- Customize animations and transitions

### Data Sources
- Add new API endpoints by creating similar fetch functions
- Modify the display functions to handle different data structures
- Add new cards to the dashboard grid

### Functionality
- Adjust auto-refresh intervals
- Add error retry mechanisms
- Implement data caching for better performance

## 🔄 How It Works

1. **Page Load**: Automatically fetches data from both APIs
2. **Weather Data**: Displays temperature, conditions, and atmospheric data
3. **News Feed**: Shows latest articles with metadata
4. **User Interaction**: Manual refresh buttons for each section
5. **Error Handling**: Falls back to mock data if APIs fail
6. **Auto-refresh**: Updates data every 10 minutes

## 📊 Project Structure

```
api-integration-dashboard/
├── index.html          # Main HTML file with embedded CSS and JavaScript
├── README.md           # This file
└── assets/            # Optional: separate CSS/JS files
    ├── style.css      # External stylesheet (optional)
    └── script.js      # External JavaScript (optional)
```

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [OpenWeatherMap](https://openweathermap.org/) for weather data API
- [NewsAPI](https://newsapi.org/) for news articles API
- Modern web design inspiration from contemporary UI/UX trends

## 📧 Contact

## 📬 Contact

Feel free to reach out via email: [sivakumar041203@gmail.com](mailto:sivakumar041203@gmail.com)


Project Link: [https://github.com/yourusername/api-integration-dashboard](https://github.com/sivakumar0412/API-INTEGRATION)

---

⭐ If you found this project helpful, please give it a star on GitHub!

## OUTPUT:

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/b5b44dde-8aac-4df9-9a25-480ae99fdeaf" />

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/4e4ed1e1-a35d-4c3c-9038-027f4285d089" />
