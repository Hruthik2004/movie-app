# Movie Search App

## 📌 Overview
The **Movie Search App** is a React Native mobile application that allows users to search for movies, view details such as ratings and posters, and save their favorite movies. It utilizes the **OMDb API** for fetching movie data.

## 🚀 Features
- 🔍 **Search Movies** by title.
- 📋 **Display Movie List** with poster and title.
- 🎥 **Movie Details Page** with poster, title, year, genre, and IMDb rating.
- ⭐ **Save Favorites** using AsyncStorage.
- 🔄 **Load More Movies** when scrolling down.

## 🛠 Tech Stack
- **React Native** (Mobile UI Framework)
- **React Navigation** (Screen Navigation)
- **Fetch / Axios** (API Requests)
- **AsyncStorage** (Local Storage for Favorites)
- **OMDb API** (Movie Database)
- **Styled Components / NativeBase** (UI Enhancements)

## 📥 Installation & Setup
### 1️⃣ Clone the Repository
```sh
git clone https://github.com/your-username/movie-search-app.git
cd movie-search-app
```

### 2️⃣ Install Dependencies
```sh
npm install  # or yarn install
```

### 3️⃣ Get OMDb API Key
- Go to [OMDb API](https://www.omdbapi.com/) and get a free API key.
- Create a `.env` file and add:
```sh
API_KEY=your_api_key_here
```

### 4️⃣ Run the App
#### For Android:
```sh
npx react-native run-android
```
#### For iOS:
```sh
npx pod-install
npx react-native run-ios
```


## 📜 Folder Structure
```
MovieSearchApp/
│-- src/
│   │-- components/
│   │   ├── MovieItem.js
│   │-- screens/
│   │   ├── HomeScreen.js
│   │   ├── MovieDetailsScreen.js
│   │-- utils/
│   │   ├── api.js
│-- App.js
│-- package.json
```

## 🚀 Future Enhancements
- 🎭 Add **Dark Mode**.
- 🔑 Implement **User Authentication** for syncing favorites.
- 📽 Integrate **TMDb API** for better movie data.

## 📜 License
This project is licensed under the **MIT License**.

## 🤝 Contributing
Pull requests are welcome! For major changes, open an issue first to discuss what you'd like to change.

## 📧 Contact
For queries, reach out at **hruthike@gmail.com**.

