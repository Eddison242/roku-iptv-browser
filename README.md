# Roku IPTV Browser

## Comprehensive Documentation

### Features
- Streamlined navigation for IPTV content.
- Support for various media formats.
- User-friendly interface accessible on Roku devices.

### Installation
1. Download the IPTV Browser from the GitHub repository.
2. Upload the package to your Roku device.
3. Install the channel and follow the setup instructions.

### Usage Guide
- Navigate to the main menu to select your channel.
- Use the remote to search for IPTV content.

### M3U Format
- The M3U format is a text file that contains the URLs of live TV streams.
- Sample format:
  ```
  #EXTM3U
  #EXTINF:-1, Channel Name
  http://example.com/stream
  ```

### Configuration
- Open the settings to configure network and playback options.
- You can add multiple M3U playlists for organization.

### Troubleshooting
- If the channel won't load, check your internet connection.
- Ensure the M3U URLs are valid.

### Security
- Be cautious with public M3U links; use trusted sources only.
- Regularly update the application to the latest version for security patches.

### API Reference
- The APIs provided allow integration with other applications.
- Endpoints include:
  - `GET /channels`
  - `POST /play`

### Contributing Guidelines
1. Fork the repository.
2. Create a new branch for your feature.
3. Make your changes and submit a pull request.