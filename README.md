# NetflixGPT

A modern Netflix clone enhanced with GPT-powered search and recommendations.

## 📝 Overview

The NetflixGPT App is an AI-driven platform that enhances the Netflix experience. It leverages OpenAI's GPT-3.5 model to provide personalized content recommendations. This project is for Netflix enthusiasts seeking a more engaging and customized streaming experience.

It empowers users to explore content effortlessly, engage in natural language interactions, and gain a deeper understanding of their favorite shows and movies. Whether you're a seasoned Netflix user or just starting your streaming journey, this app is designed to make your entertainment experience more enjoyable and enriching.

## 🎬 Key Components

- **Header**: Navigation and user account controls
- **Main Movie**: Featured content with trailer in background
- **Title and Description**: Information about the featured content
- **Movie Suggestions**: AI-powered content recommendations
- **Movies Lists**: Multiple categorized content rows
- **Netflix GPT**: AI-powered search functionality
- **Search Bar**: Natural language content discovery

## 🚀 Features

- **User Authentication**: Secure login and signup functionality
- **Browse Movies & Shows**: Explore a vast library of content
- **GPT-Powered Search**: Natural language search for finding content
- **Personalized Recommendations**: AI-driven content suggestions
- **Responsive Design**: Optimized for all device sizes
- **Multi-language Support**: Content available in multiple languages

## 🛠️ Tech Stack

- **Frontend**: React.js
- **State Management**: Redux Toolkit
- **Styling**: Tailwind CSS
- **Authentication**: Firebase Auth
- **API Integration**: TMDB API for movie data
- **AI Integration**: OpenAI GPT API
- **Deployment**: Firebase Hosting

## 📋 Prerequisites

- Node.js (v14 or later)
- npm or yarn
- Firebase account
- TMDB API key
- OpenAI API key

## 🔧 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Aayush7213/NetflixGPT.git
   cd NetflixGPT
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the root directory with the following variables:
   ```
   REACT_APP_FIREBASE_API_KEY=your_firebase_api_key
   REACT_APP_FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
   REACT_APP_FIREBASE_PROJECT_ID=your_firebase_project_id
   REACT_APP_FIREBASE_STORAGE_BUCKET=your_firebase_storage_bucket
   REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_firebase_messaging_sender_id
   REACT_APP_FIREBASE_APP_ID=your_firebase_app_id
   REACT_APP_TMDB_API_KEY=your_tmdb_api_key
   REACT_APP_OPENAI_API_KEY=your_openai_api_key
   ```

4. Start the development server:
   ```bash
   npm start
   ```

## 🌐 Usage

1. Sign up for a new account or log in with existing credentials
2. Browse through different categories of movies and shows
3. Use the GPT search feature to find content using natural language
4. Get personalized recommendations based on your viewing history
5. Add content to your watchlist for later viewing

## 📱 Screenshots

![Home Screen](https://via.placeholder.com/800x450?text=Netflix+GPT+Home+Screen)
![GPT Search](https://via.placeholder.com/800x450?text=GPT+Search+Feature)
![Movie Details](https://via.placeholder.com/800x450?text=Movie+Details+Page)

## 🔍 Project Structure

```
NetflixGPT/
├── public/
├── src/
│   ├── components/
│   │   ├── Browse.js
│   │   ├── GPTSearch.js
│   │   ├── Header.js
│   │   ├── Login.js
│   │   ├── MovieCard.js
│   │   └── ...
│   ├── utils/
│   │   ├── constants.js
│   │   ├── firebase.js
│   │   └── ...
│   ├── hooks/
│   ├── store/
│   │   ├── appStore.js
│   │   └── ...
│   ├── App.js
│   └── index.js
├── .env
├── .gitignore
├── package.json
└── README.md
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👏 Acknowledgments

- [TMDB API](https://www.themoviedb.org/documentation/api) for providing movie data
- [OpenAI](https://openai.com/) for GPT API
- [Firebase](https://firebase.google.com/) for authentication and hosting
- [Tailwind CSS](https://tailwindcss.com/) for styling

## 📞 Contact

Aayush - [@YourTwitter](https://twitter.com/YourTwitter) - your.email@example.com

Project Link: [https://github.com/Aayush7213/NetflixGPT](https://github.com/Aayush7213/NetflixGPT)
