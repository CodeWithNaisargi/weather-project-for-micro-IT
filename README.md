# Weather Forecast Application

A beautiful weather application that shows current weather and 5-day forecast with animated backgrounds.

## Features

- Current weather display with animated backgrounds
- 5-day weather forecast
- Responsive design
- Weather-based animations (rain, snow, clouds, sun)
- Dark mode support
- Reduced motion support
- Search functionality for any city

## Technologies Used

- HTML5
- CSS3
- JavaScript
- OpenWeather API

## Deployment

This project is ready to be deployed on Vercel. Follow these steps:

1. Install Vercel CLI (optional):
   ```bash
   npm i -g vercel
   ```

2. Deploy using one of these methods:
   - Using Vercel CLI:
     ```bash
     vercel
     ```
   - Using Vercel Dashboard:
     1. Push this code to your GitHub repository
     2. Import the repository in Vercel Dashboard
     3. Deploy

## Environment Variables

Make sure to set up these environment variables in your Vercel project:
- `OPENWEATHER_API_KEY`: Your OpenWeather API key

## Local Development

1. Clone the repository
2. Open index.html in your browser
3. For API requests to work locally, replace the API key in the code with your own

## API Key Security Note

For production, it's recommended to move the API key to environment variables and use a backend proxy to make API calls.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

MIT License 