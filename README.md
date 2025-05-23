
📱 Flutter QR Code Scanner & Generator
A simple and clean Flutter app to scan and generate QR codes with ease. Built using Flutter and Dart, this app supports real-time QR code scanning and allows users to create custom QR codes instantly.


✨ Features
🔍 Real-time QR code scanner using device camera

🧾 QR code generator with custom text input

💾 Save generated QR codes to device

🌙 Clean UI with dark/light mode support

✅ Works on both Android & iOS

📸 Screenshots

Scanner	Generator
🚀 Getting Started
1. Clone the repo
bash
Copy
Edit
git clone https://github.com/your-username/qr_flutter_app.git
cd qr_flutter_app
2. Install dependencies
bash
Copy
Edit
flutter pub get
3. Run the app
bash
Copy
Edit
flutter run
📦 Dependencies
qr_flutter – for generating QR codes

qr_code_scanner – for scanning QR codes

path_provider – for saving files

permission_handler – to request camera/storage permissions

📁 Folder Structure
css
Copy
Edit
lib/
 ┣ main.dart
 ┣ screens/
 ┃ ┣ scanner_screen.dart
 ┃ ┗ generator_screen.dart
 ┗ widgets/
    ┗ custom_button.dart
🛡️ Permissions
Make sure to add the required permissions in AndroidManifest.xml:

xml
Copy
Edit
<uses-permission android:name="android.permission.CAMERA" />
<uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE"/>
And for iOS, update Info.plist:

xml
Copy
Edit
<key>NSCameraUsageDescription</key>
<string>We need camera access to scan QR codes.</string>
🙋‍♂️ Author
Kumarjit Hazra
📧 kumarjithazra465@gmail.com
🔗 LinkedIn
🎬 YouTube

📝 License
This project is licensed under the MIT License - see the LICENSE file for details.
