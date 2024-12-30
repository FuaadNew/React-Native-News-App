# News Reader App

This is a simple **News Reader** app built with **React Native** that fetches real-time news from the **News API**. The app allows users to read news articles based on different categories such as General, Business, Technology, and Sports. Users can also click on a news item to see more details in a modal and visit the full article.

## Features
- Fetches news articles from the News API based on user-selected categories.
- Supports categories such as General, Business, Technology, and Sports.
- Displays a list of articles with images, descriptions, and categories.
- Users can click on "Read more" to see a detailed modal with the full content of the article.
- Allows users to filter the news by category using a picker.
- Uses **React Native**, **Axios** for API calls, and **React Native Elements** for UI components.

## Screenshots
![News Reader App](link_to_screenshot)

## Installation

### Prerequisites
1. **Node.js** and **npm** (Node Package Manager)
2. **Expo CLI** (if you're using Expo)
3. **React Native Development Environment** set up (if you're not using Expo)

### Steps to Run the App

1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/yourusername/news-app.git
    ```

2. Navigate to the project directory:
    ```bash
    cd news-app
    ```

3. Install dependencies:
    ```bash
    npm install
    ```

4. Install additional packages for React Native Elements and Axios:
    ```bash
    npx expo install react-native-elements react-native-picker-select axios
    ```

5. Start the app:
    ```bash
    npx expo start
    ```

    This will start the Expo development server. You can now run the app on an Android/iOS emulator or on a physical device using the Expo Go app.

    For iOS (if you're using a physical device or simulator):
    ```bash
    npx react-native run-ios
    ```

    For Android:
    ```bash
    npx react-native run-android
    ```

6. Open the app in the browser using `w` in the terminal.

## Usage

1. Upon launching the app, users will be presented with a **News Category Picker** to filter news by General, Business, Technology, or Sports.
2. The app fetches and displays the latest articles in the selected category.
3. Each article has a title, description, image, and category.
4. Clicking on "Read More" will open a modal with detailed content and a link to the full article.

## Technologies Used
- **React Native**: For building the mobile app.
- **Axios**: To make HTTP requests to the News API.
- **React Native Elements**: For UI components like cards, buttons, and icons.
- **React Navigation**: For navigation between different screens (if applicable).
- **News API**: To fetch real-time news articles.



