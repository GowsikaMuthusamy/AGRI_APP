# AgriApp

AgriApp is a mobile application developed using Dart and Flutter, designed to assist farmers with various agricultural needs. The app provides features such as weather updates, online product purchasing, community interaction, and personalized farming guidance. It aims to empower farmers with technology, making farming more efficient and sustainable.

## Features

### 1. **Authentication**
- Login and Registration for farmers and buyers.
### 2. **Home Page**
- **Weather Updates**: Displays current weather conditions and forecasts.
- **Recommended Products**: Showcases products based on farming needs.
- **Agricultural News**: Provides the latest updates and news related to farming.

### 3. **Shop**
- Browse and purchase farming tools, seeds, fertilizers, and more.
- Add products to the cart with details such as quantity, price, discounts, and images.
- Secure checkout process.

### 4. **Weather Page**
- Detailed weather predictions for farming decisions.
- Navigation to `DetailedWeatherPage.dart` for more information.

### 5. **Community Page**
- A platform for farmers to interact, share experiences, and seek advice.

### 6. **Profile Management**
- Personalized dashboards for farmers.
- Manage personal details, purchase history, and farming preferences.

### 7. **Additional Features**
- Information on sustainable farming practices and organic gardening.
- Farmers can list and sell their products directly to consumers.

## Installation

### Prerequisites
- Flutter SDK installed on your machine.
- A code editor like Visual Studio Code or Android Studio.
- Dart language support.

### Steps to Run the Application
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/agriapp.git
   ```
2. Navigate to the project directory:
   ```bash
   cd agriapp
   ```
3. Install dependencies:
   ```bash
   flutter pub get
   ```
4. Run the app:
   ```bash
   flutter run
   ```

## Folder Structure
```
AgriApp/
├── lib/
│   ├── main.dart           # Entry point of the application
│   ├── screens/            # Contains all the app screens
│   │   ├── home.dart       # Home screen
│   │   ├── shop.dart       # Shop screen
│   │   ├── community.dart  # Community interaction screen
│   │   └── weather.dart    # Weather details screen
│   ├── models/             # Data models for products, weather, etc.
│   ├── services/           # API and Firebase integration
│   └── widgets/            # Reusable UI components
├── assets/
│   ├── images/             # Image assets for the app
│   └── icons/              # Icon assets for the app
├── pubspec.yaml            # Flutter dependencies and assets
└── README.md               # Project documentation
```

## Technologies Used
- **Flutter**: Frontend framework for building the app.
- **Dart**: Programming language for Flutter.

## Screenshots

### Home Page
![Home Page](assets/images/home_page.png)

### Shop Page
![Shop Page](assets/images/shop_page.png)

### Community Page
![Community Page](assets/images/community_page.png)

## Future Enhancements
- Integration of AI-based crop disease detection.
- Multilingual support for better accessibility.
- Real-time chat functionality for farmers and experts.

## Contributing
Contributions are welcome! If you want to contribute to this project, please fork the repository and create a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For any queries or suggestions, please contact:
- Email: support@agriapp.com
- GitHub: [yourusername](https://github.com/yourusername)
