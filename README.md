# BC MLA Contact App - Medical Wait Times

A web application that helps British Columbia residents find their MLA (Member of the Legislative Assembly) and generate an email about excessive medical wait times.

## Features

- 🔍 **Find Your MLA**: Enter your address or postal code to automatically find your electoral district and MLA
- 📧 **Email Generation**: Automatically generates a professional email addressing medical wait time concerns
- 📋 **Easy Copy**: One-click copy functionality to easily send the email from your email provider
- 🎨 **User-Friendly Interface**: Clean, step-by-step interface with progress indicators

## How to Use

1. **Open the App**: Open `index.html` in any modern web browser
2. **Enter Your Location**: Type your full address or postal code (e.g., "V6B 1A1")
3. **Find Your MLA**: Click "Find My MLA" to search
4. **Confirm Information**: Review your MLA's information and confirm it's correct
5. **Generate Email**: Click "Yes, Generate Email" to create a pre-written message
6. **Copy and Send**: Click "Copy Email" and paste it into your email client to send to your MLA

## Technical Details

### APIs Used

- **Represent API** (represent.opennorth.ca): Used to find BC MLAs by postal code or coordinates
- **Nominatim/OpenStreetMap**: Used for geocoding full addresses to coordinates

### Browser Requirements

- Modern web browser with JavaScript enabled
- Internet connection required for API calls
- Clipboard API support for copy functionality (supported in all modern browsers)

### Privacy

This application:
- Does not store or transmit your personal information
- Makes API calls directly from your browser to public APIs
- Does not use cookies or tracking
- Does not send emails automatically (you control when and how to send)

## Development

The application is a single-page HTML file with embedded CSS and JavaScript. No build process or dependencies required.

### File Structure

```
waiting-times/
├── index.html          # Main application file
├── README.md          # This file
└── LICENSE            # License information
```

## Deployment

To deploy this application:

1. **GitHub Pages**: Simply enable GitHub Pages in your repository settings
2. **Static Hosting**: Upload `index.html` to any static hosting service (Netlify, Vercel, etc.)
3. **Local Use**: Open `index.html` directly in a web browser

## Contributing

Contributions are welcome! Feel free to submit issues or pull requests.

## License

See LICENSE file for details.

## Acknowledgments

- Represent API by OpenNorth for providing Canadian electoral district data
- Elections BC for electoral district information
- BC Legislative Assembly for MLA contact information
