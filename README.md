<h1>🎬 Movie App – React + Vite + Tailwind CSS</h1>

A simple movie browsing app built using React (Vite) where users can choose a language (Hindi, Bengali, English) and view movie lists along with posters.

<h3>🚀 Features</h3>

Choose language (Hindi / Bengali / English)

Display movies based on selected language

Movie posters + titles

Responsive UI

Clean Tailwind styling


<h3>📁 Project Structure</h3>

src/
 ├── App.jsx        # Main React component
 ├── main.jsx       # React initialization
 ├── index.css      # Tailwind included here
 ├── App.css        
public/
index.html
vite.config.js

<h3>🛠️ Installation & Setup</h3>
1️⃣ Clone or download the project
git clone <your-repo-url>
cd Movie_App

2️⃣ Install dependencies
npm install

3️⃣ Install Tailwind CSS
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p

4️⃣ Configure Tailwind
Edit tailwind.config.js
export default {
  content: ["./index.html", "./src/**/*.{js,jsx,ts,tsx}"],
  theme: {
    extend: {},
  },
  plugins: [],
};

5️⃣ Add Tailwind to index.css

Replace everything in src/index.css with:

@tailwind base;
@tailwind components;
@tailwind utilities;

6️⃣ Run the development server
npm run dev


Your app opens at:

👉 http://localhost:5173/

📸 Screenshots

Add your screenshots here

📦 Build for Production
npm run build


The optimized output will be created inside:

dist/

👨‍💻 Technologies Used

React (Vite)

Tailwind CSS

JavaScript (ES6+)

🙌 Contributing

Feel free to open issues or submit pull requests.

📜 License

This project is open-source and free to use.
