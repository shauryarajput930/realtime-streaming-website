# StreamFlow - Realtime Video Streaming Website

A modern video streaming application with proxy server to bypass CORS and hotlink restrictions.

## Features

- 🎥 **Video Streaming**: Stream videos from various sources
- 🌐 **CORS Bypass**: Built-in proxy server to handle cross-origin requests
- 🎨 **Modern UI**: Clean and responsive user interface
- ⚡ **Real-time Streaming**: Optimized for smooth video playback
- 🔒 **Secure**: Proxy server handles external video requests securely

## Project Structure

```
Realtime-Streaming-website/
├── index.html          # Main HTML file
├── styles.css          # Styling and UI components
├── player.js           # Video player logic and functionality
├── server.js           # Node.js proxy server
├── .gitignore          # Git ignore rules
└── README.md           # This file
```

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone this repository:
   ```bash
   git clone <repository-url>
   cd Realtime-Streaming-website
   ```

2. Install dependencies (if any):
   ```bash
   npm install
   ```

### Running the Application

1. Start the proxy server:
   ```bash
   node server.js
   ```

2. Open your browser and navigate to:
   ```
   http://localhost:4000
   ```

## Usage

1. **Add Video URL**: Enter the video URL you want to stream
2. **Play**: Click the play button to start streaming
3. **Controls**: Use the built-in video controls for playback
4. **Fullscreen**: Enjoy fullscreen viewing experience

## API Endpoints

- `GET /` - Main application
- `GET /proxy` - Proxy endpoint for video streaming

## Configuration

The server runs on port 4000 by default. You can modify this in `server.js`:

```javascript
const PORT = 4000; // Change to your preferred port
```

## Development

### File Descriptions

- **`server.js`**: Node.js server that handles proxy requests and serves static files
- **`index.html`**: Main HTML structure with semantic markup
- **`styles.css`**: Complete styling with modern CSS features
- **`player.js`**: JavaScript logic for video player and streaming functionality

### Adding Features

- Video playlist support
- User authentication
- Video quality settings
- Subtitle support
- Download functionality

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## License

This project is open source and available under the [MIT License](LICENSE).

## Troubleshooting

### Common Issues

1. **Port Already in Use**: Change the PORT in `server.js`
2. **CORS Issues**: Ensure the proxy server is running
3. **Video Not Loading**: Check the video URL and network connection

### Support

For issues and questions, please open an issue on the GitHub repository.

---

**Built with ❤️ for seamless video streaming**
