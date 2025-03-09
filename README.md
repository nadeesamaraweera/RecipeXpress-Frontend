# RecipeXpress Frontend

**RecipeXpress** is a modern recipe discovery application that helps users find recipes based on available ingredients. This repository contains the frontend, built using **React Native with Expo**, ensuring a smooth and responsive experience across mobile devices.

## Features
- 🔐 **User Authentication** – Secure login and signup with JWT
- 🔍 **Ingredient-Based Search** – Find recipes by entering available ingredients
- 📖 **Detailed Recipe View** – Step-by-step cooking instructions
- ❤️ **Save Favorites** – Bookmark recipes for quick access
- 🕒 **Search History** – View and manage past searches

## Tech Stack
- **Frontend**: React Native (Expo)
- **State Management**: Context API
- **Navigation**: React Navigation (Stack Navigation)
- **Backend**: [RecipeXpress Backend Repository](https://github.com/nadeesamaraweera/RecipeXpress-Backend.git)

## Setup & Installation

### Prerequisites
Before setting up the project, ensure you have:
- **Node.js** (>= 16.x)
- **npm** or **yarn**
- **Expo CLI** (`npm install -g expo-cli`)
- **Android/iOS Emulator** or a physical device

### Installation Steps
### Prerequisites
Ensure you have the following installed:
- Node.js (>= 16.x)
- npm or yarn
- Expo CLI (`npm install -g expo-cli`)
- Android/iOS Emulator or Physical Device

### Installation Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/nethmiumaya/RecipeRadar-Frontend.git
   ```
2. Navigate to the project directory:
   ```sh
   cd RecipeRadar-Frontend
   ```
3. Install dependencies:
   ```sh
   npm install
   ```
   or
   ```sh
   yarn install
   ```
4. Set up environment variables by creating a `.env` file in the root directory:
   ```
   REACT_APP_API_BASE_URL=http://localhost:4000/api
   ```
5. Start the development server:
   ```sh
   expo start
   ```

## License
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more details.

