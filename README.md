# Online-Compass-Site

Website :  https://lighthearted-travesseiro-0f134e.netlify.app/
# Online Compass site

An online compass web application that utilizes your mobile device's built-in sensors to display direction, heading, and orientation in real-time. This site is designed exclusively for mobile phones and will not function on desktop computers or tablets.
![output-site](https://github.com/user-attachments/assets/a5b249ef-326a-46db-aa63-8d3c968df3b8)

## Features

- **Real-Time Direction**: Displays your current heading (e.g., North, South) based on the device's compass sensor.
- **Visual Compass**: Interactive needle that rotates to indicate magnetic north.
- **Accuracy Indicator**: Shows the reliability of the compass reading.
- **Mobile-Only**: Optimized for touch interfaces and mobile browsers; incompatible with non-mobile devices.
- **No Installation Required**: Access directly via your mobile browser—no app store downloads needed.

## How It Works

The compass relies on the HTML5 DeviceOrientation API to access your phone's gyroscope and magnetometer. It calculates the device's orientation relative to magnetic north, providing accurate directional data. Note that accuracy depends on your device's hardware and environmental factors (e.g., proximity to metal objects).

## Requirements

- **Device**: Smartphone with a built-in compass sensor (most modern Android and iOS devices qualify).
- **Browser**: A mobile browser that supports the DeviceOrientation API, such as:
  - Chrome (Android/iOS)
  - Safari (iOS)
  - Firefox (Android/iOS)
- **Permissions**: Grant location and sensor access when prompted by your browser for accurate readings.
- **Internet Connection**: Required only for initial page load; the compass functions offline once loaded.

## Usage

1. Open the site URL in your mobile browser.
2. Allow permissions for device orientation and location if requested.
3. Hold your phone flat and level for the best accuracy.
4. The compass needle will point to magnetic north, and the heading will update in real-time as you rotate the device.
5. Tap the screen to calibrate if readings seem off (follow on-screen instructions).

**Troubleshooting**:
- If the compass doesn't work, ensure your device has a compass sensor and that you're using a supported browser.
- Disable battery-saving modes or apps that might interfere with sensors.
- For iOS devices, ensure "Location Services" are enabled in Settings > Privacy.

## Browser Support

- Fully supported on iOS 13+ and Android 7+ with compatible browsers.
- Not supported on desktop browsers or tablets due to lack of mobile sensors.

## Contributing

This is an open-source project. To contribute:
1. Fork the repository.
2. Make your changes.
3. Submit a pull request with a description of your improvements.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Disclaimer

This tool is for informational purposes only. Compass readings may vary due to device calibration, magnetic interference, or environmental factors. Always verify directions with multiple sources for critical navigation.
