# BDIX Media Player

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Platform](https://img.shields.io/badge/platform-cross--platform-lightgrey.svg)

BDIX Media Player is a free and open-source, cross-platform streaming media player and server solution that supports multiple streaming platforms including Facebook, YouTube, and Twitch. It provides a robust, customizable HTML5 player with advanced features for both broadcasters and viewers.

## 🚀 Features

- **Multi-Platform Streaming Integration**
  - Facebook Live integration
  - YouTube Live streaming
  - Twitch streaming support
  - Custom RTMP/HLS endpoints

- **Advanced Player Capabilities**
  - HTML5 player with custom controls
  - Adaptive bitrate streaming
  - Multi-quality resolution support
  - Live-to-VOD transition
  - Chat overlay integration

- **Global CDN Integration**
  - 50+ edge locations worldwide
  - 65Tb/s network capacity
  - Optimal global content delivery
  - Low-latency streaming

- **Security & Control**
  - Geographic access control
  - Domain restriction
  - Custom authentication
  - Secure playback options

- **Analytics & Monitoring**
  - Real-time viewer statistics
  - Bandwidth usage tracking
  - Peak time analysis
  - Performance metrics

## 📋 Requirements

- Modern web browser with HTML5 support
- Internet connection
- Supported streaming source (HLS/M3U8/MP4)

## 🔧 Installation

1. Clone the repository:
```bash
git clone https://github.com/likhonisaac/bdix-player.git
```

2. Navigate to the project directory:
```bash
cd bdix-player
```

3. Open `index.html` in your web browser or deploy to your web server.

## 💻 Usage

### Basic Implementation

```html
<iframe 
  src="https://your-domain.com/embed?type=m3u8&src=YOUR_STREAM_URL" 
  width="100%" 
  height="400" 
  frameborder="0" 
  allowfullscreen>
</iframe>
```

### Advanced Configuration

```javascript
const player = new BDIXPlayer({
  container: '#player',
  source: 'YOUR_STREAM_URL',
  autoplay: true,
  muted: false,
  controls: true,
  adaptiveBitrate: true
});
```

## 🔌 API Reference

### Stream Types
- `m3u8` - HLS streams
- `mp4` - Direct video files
- `rtmp` - RTMP streams

### Player Options
```javascript
{
  container: string,      // Player container ID
  source: string,        // Stream URL
  autoplay: boolean,     // Enable autoplay
  muted: boolean,        // Start muted
  controls: boolean,     // Show controls
  adaptiveBitrate: boolean, // Enable ABR
  chat: boolean,         // Enable chat overlay
  logo: string,          // Custom logo URL
  theme: string          // Player theme
}
```

## 📱 Responsive Design

The player automatically adjusts to different screen sizes:
- Desktop: Full-width with customizable dimensions
- Tablet: Responsive scaling with optimal controls
- Mobile: Mobile-optimized interface with touch controls

## 🔒 Security Features

- **Domain Restriction**: Limit player embedding to specific domains
- **Geographic Restrictions**: Control access by location
- **Token Authentication**: Secure playback with temporary tokens
- **Encryption**: Support for encrypted streams

## 📊 Analytics Integration

Monitor your streams with real-time analytics:
- Concurrent viewers
- Bandwidth usage
- Quality metrics
- Geographic distribution
- Device statistics

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## 🙏 Acknowledgments

- [HLS.js](https://github.com/video-dev/hls.js/) for HLS playback
- [Plyr](https://github.com/sampotts/plyr) for the player interface
- [Tailwind CSS](https://tailwindcss.com/) for styling

## 📞 Support

For support, please create an issue in the GitHub repository or contact us at:
- GitHub Issues: [https://github.com/likhonisaac/bdix-player/issues](https://github.com/likhonisaac/bdix-player/issues)
- Email: me@likhon.dev

---

Made with ❤️ by the BDIX Media Player Team
