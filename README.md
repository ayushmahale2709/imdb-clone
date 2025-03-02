
### 🎬 IMDb Clone  

A simple movie search app using the **OMDb API**, built with **React** and **Vite**. Users can search for movies, view details, and save favorites.

---

## 📌 Features  

✅ Search for movies using the **OMDb API**  
✅ View movie details, including **year, genre, director, actors, and IMDb rating**  
✅ Add movies to a **Favorites list**  
✅ Store favorites **locally** using `localStorage`  
✅ Clean **UI with responsive design**  

---

## 🛠️ Tech Stack  

🔹 **React** - Frontend library  
🔹 **Vite** - Build tool for fast development  
🔹 **Axios** - Fetching movie data from the OMDb API  
🔹 **LocalStorage** - Save favorites persistently  
🔹 **CSS** - Styling for a modern look  

---

## 🚀 Getting Started  

Follow these steps to set up the project on your local machine.

### 1️⃣ Clone the repository  

```sh
git clone https://github.com/ayushmahale2709/imdb-clone.git
cd imdb-clone
```

### 2️⃣ Install dependencies  

```sh
npm install
```

### 3️⃣ Create an `.env` file  

Make sure to create a **`.env`** file in the root directory and add your OMDb API key:

```
VITE_OMDB_API_KEY=your_api_key_here
```

🚨 **Important:** Never commit your `.env` file to GitHub for security reasons.

### 4️⃣ Run the app  

```sh
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

---

## 📸 Screenshots  

🔹 **Homepage:**  
> *(Add a screenshot here)*  

🔹 **Movie Details Page:**  
> *(Add a screenshot here)*  

---

## 🛠️ Environment Variables  

| Variable | Description |
|----------|-------------|
| `VITE_OMDB_API_KEY` | Your API key from [OMDb API](https://www.omdbapi.com/) |

---

## 🤔 Troubleshooting  

### ❌ API Key Not Working?  
- Ensure your **API key** is valid. Register at [OMDb API](https://www.omdbapi.com/apikey.aspx)  
- Check if `.env` is properly loaded by adding `console.log(import.meta.env.VITE_OMDB_API_KEY);`  

### ❌ Movies Not Fetching?  
- Make sure you are **using the correct API URL**  
- Check your **internet connection**  
- Restart the development server after updating `.env`:  
  ```sh
  npm run dev
  ```

---

## 👨‍💻 Contributing  

🔹 Feel free to **fork** the repo and submit **pull requests**!  
🔹 Open an **issue** if you find bugs or have feature requests.  

---

## 📜 License  

This project is **MIT licensed**.  

---

Let me know if you need any modifications! 🚀🔥
