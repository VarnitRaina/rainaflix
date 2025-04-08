🎬 RainaFlix
RainaFlix is a movie browsing web application that fetches the latest popular movies using an external API. Users can explore movies on the Home Page and mark their favorite ones to store them separately on the Favorites Page.

🚀 Features
🔍 Browse Movies – Displays trending movies fetched from an external API.

❤️ Favorite Movies – Save movies to a personalized favorites list.

🔄 Dynamic UI – Responsive and sleek user interface.

⚡ Fast & Interactive – Optimized performance for a smooth experience.

🛠️ Installation & Setup
1️⃣ Clone the Repository
sh
Copy
Edit
git clone https://github.com/VarnitRaina/rainaflix.git
cd rainaflix
2️⃣ Install Dependencies
sh
Copy
Edit
npm install
3️⃣ Set Up API Keys (Prevent Leaks!)
Create a .env file in the project root:

ini
Copy
Edit
API_KEY=your_api_key_here
Update .gitignore to prevent pushing secrets:

bash
Copy
Edit
.env
node_modules
4️⃣ Run the Development Server
sh
Copy
Edit
npm start
The project will run at http://localhost:3000.

🚀 Deployment
To deploy the project:

Build the project:

sh
Copy
Edit
npm run build
Push to GitHub:

sh
Copy
Edit
git add .
git commit -m "Initial commit"
git push origin main
Deploy to Vercel/Netlify (Optional)

📌 Tech Stack
Frontend: Vite, React.js, JSX, CSS

State Management: React Context API

Routing: React Router (if used, otherwise remove this)

Styling: CSS Modules

API Handling: Axios (if used, otherwise fetch API)

Environment Variables: .env (Vite Environment Variables)

External API: The Movie Database (TMDb)

Development Tools: ESLint, Vite.js

📜 License
This project is open-source and free to use.

