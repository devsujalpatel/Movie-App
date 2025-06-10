# 🎬 Movie App

A sleek and responsive movie search application powered by **Appwrite** for backend services and styled with modern UI principles. Users can search for movies, view details like posters, descriptions, and ratings — all in a fast and interactive interface.

🔗 **Live Demo**: [cinesearchhmovies.netlify.app](https://cinesearchhmovies.netlify.app/)

## ✨ Features

- 🔍 **Search Movies** by title in real-time  
- 🎥 **Display Movie Details** like title, year, rating, and posters  
- ☁️ **Appwrite Integration** for secure backend operations  
- 📱 **Responsive Design** for all screen sizes  
- ⚡ **Fast and Clean UI** built with modern web technologies  

## 🛠️ Built With

- **React.js** – UI library  
- **Appwrite** – Backend-as-a-service for data storage & API  
- **Tailwind CSS** – Utility-first CSS framework for styling  
- **TMDB API** *(assumed)* – To fetch movie data  
- **Vite** – Lightning-fast dev server and build tool  

## 🧱 Project Structure

```bash

Movie-App/
├── public/
├── src/
│ ├── components/
│ ├── pages/
│ ├── appwrite.ts/ # API calls and Appwrite logic
│ ├── App.tsx
│ ├── main.tsx
├── .env
├── tailwind.config.js
├── vite.config.ts
├── package.json
└── README.md
```
bash

## ⚙️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/devsujalpatel/Movie-App.git
cd Movie-App
```
2. Install Dependencies
```bash
npm install
```
3. Set Up Environment Variables
Create a .env file in the root directory and add your Appwrite credentials:

env
Copy
Edit
VITE_APPWRITE_ENDPOINT=https://cloud.appwrite.io/v1
VITE_APPWRITE_PROJECT_ID=your_project_id
VITE_APPWRITE_DATABASE_ID=your_database_id
VITE_APPWRITE_COLLECTION_ID=your_collection_id
Replace with your actual Appwrite project values.

4. Start the Development Server
bash
Copy
Edit
npm run dev
Visit http://localhost:5173 in your browser.

🚀 Deployment
This app is easily deployable to Netlify, Vercel, or any static hosting platform. The current live version is hosted on Netlify.

🧑‍💻 Author
Sujal Patel – @devsujalpatel

📄 License
This project is licensed under the MIT License.

🙌 Acknowledgements
Appwrite

The Movie Database API

Tailwind CSS
