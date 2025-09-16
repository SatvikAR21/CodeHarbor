⚓ CodeHarbor

A lightweight version control system built with the MERN stack (MongoDB, Express.js, React.js, Node.js).
CodeHarbor enables developers to initialize repositories, track changes, commit updates, and collaborate, all from a custom-built platform.

✨ Features

🔧 Repository Management – Initialize, add, commit, push, pull, and revert changes

👤 User Authentication – JWT-based login/signup and secure access to repositories

📂 Project Tracking – Keep history of commits and track different versions

🌐 Web UI – Clean, responsive React.js frontend for managing projects

☁ Cloud Integration – AWS support for storage and deployment

🛠 Tech Stack

Frontend: React.js, TailwindCSS

Backend: Node.js, Express.js

Database: MongoDB (Mongoose ODM)

Authentication: JWT, bcrypt

Cloud & Storage: AWS S3 (for repo data backup)

📦 Installation & Setup

Clone the repository:

git clone https://github.com/your-username/codeharbor.git
cd codeharbor


Install dependencies for backend:

cd backend
npm install


Install dependencies for frontend:

cd frontend
npm install


Create a .env file in backend/ with:

MONGO_URI=your_mongodb_uri
JWT_SECRET_KEY=your_secret_key
AWS_ACCESS_KEY_ID=your_key
AWS_SECRET_ACCESS_KEY=your_secret
PORT=5000


Start the backend:

cd backend
npm start


Start the frontend:

cd frontend
npm start


Visit 👉 http://localhost:3000

🚀 Usage

Signup/Login → Create a user account

Create Repository → Initialize your project

Commit Changes → Save and track updates

Push/Pull → Sync your work with CodeHarbor

Revert → Roll back to an older commit

📸 Screenshots

(Add UI screenshots here once frontend is polished — signup, repo view, commit history)

📌 Roadmap

 Branching support

 Collaboration (invite contributors)

 Code diffs & file viewer

 CI/CD integrations

🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to fork this repo and submit a PR.

🧑‍💻 Author

Satvik Gupta

LinkedIn: linkedin.com/in/satvikgupta

GitHub: github.com/your-username

⭐ Support

If you find this project useful, don’t forget to star ⭐ the repo!
