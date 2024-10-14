🎶 LilyGO T5 E-Paper Spotify Controller
Welcome to the LilyGO T5 E-Paper Spotify Controller project! 🎧 Control your Spotify playlist with style using a sleek e-paper display. No more looking for your phone or fiddling with apps — just pure, minimalistic music control 🎵.

✨ Features
🖥️ E-Paper Display: View the current track, artist, and album on a crisp, low-power display.
⏯️ Basic Playback Controls: Play, pause, skip, and rewind with ease.
🔊 Volume Adjustment: Use buttons to adjust the volume right from the e-paper display!
🌐 WiFi Integration: Connects to your Spotify account via WiFi and updates in real-time.
📚 Requirements
LilyGO T5 4.7" E-Paper Display 🎨
Spotify Developer Account 🎧
Arduino IDE ⚙️
WiFi connection 🌐
🚀 Getting Started
Clone the repo: Get the code by cloning this repository to your local machine.

bash
Copier le code
git clone https://github.com/yourusername/spotify-controller.git
Install the Libraries: You’ll need the following libraries:

TouchDrvGT911 library 📚
epd_driver library 📚
firasans library 📚
lilygo library 📚
Install these using the Arduino Library Manager for an easy setup.

Set Up Spotify Credentials: You’ll need to grab your Client ID and Secret from your Spotify Developer Dashboard.

Flash the Code: Open the project in Arduino IDE and upload the code to your LilyGO T5.

Connect to WiFi: Input your WiFi credentials in the code and let the magic happen! ✨

🔧 Configuration
You'll need to configure the following:

Spotify API Credentials: Add your Client ID, Secret, and a Redirect URI in the config.h file.
WiFi Details: Add your network SSID and password in the code to get the controller connected.
🎯 Goals
Control Your Music Effortlessly: Switch songs and adjust volume without touching your phone or laptop 📱.
Stay Minimalistic: Enjoy the simplicity of the e-paper display showing just the essentials 🎵.
💡 Future Plans
Add album art display 📀.
Integrate with more streaming services (Apple Music, Tidal, etc.) 🎶.
Customize button functionality for personalized controls 🛠️.
🤝 Contributing
Contributions are always welcome! Feel free to open an issue or submit a pull request if you have ideas to improve the project 💡.
