🚀 Node.js TypeScript Server Boilerplate

A lightweight and scalable boilerplate for building modern Node.js applications using TypeScript. Designed for rapid development, clean architecture, and production-ready best practices.

🌟 Features
⚡ TypeScript – Strong typing for safer and cleaner code
🚀 Express.js – Fast, minimal, and flexible web framework
🧹 ESLint + Prettier – Consistent code quality and formatting
🧪 Jest – Simple and reliable testing setup
🌍 dotenv-flow – Easy environment variable management
🍃 Mongoose – Elegant MongoDB object modeling
📝 Winston – Powerful and customizable logging
📁 Clean project structure for scalability
📦 Tech Stack
Node.js
TypeScript
Express.js
MongoDB + Mongoose
Jest
ESLint
Prettier
Docker
🚀 Getting Started
1️⃣ Clone Repository
git clone https://github.com/yourusername/base_server.git
cd base_server

2️⃣ Install Dependencies
npm install

3️⃣ Setup Environment Variables

Copy example file:

cp .env.example .env


Then configure your values inside .env

▶️ Run Development Server
npm run start:dev


Server will start on:

http://localhost:5000

🛠️ Available Scripts
Command	Description
npm run start:dev	Start development server
npm run build	Compile TypeScript project
npm run start	Run production build
npm run test	Run unit tests
npm run lint	Check lint errors
npm run lint:fix	Auto-fix lint issues
npm run format:check	Check formatting
npm run format:fix	Auto-format code
npm run migrate:dev	Run dev migrations
npm run migrate:prod	Run production migrations
npm run dockerize:dev	Build Docker image
📂 Recommended Structure
src/
 ┣ config/
 ┣ controllers/
 ┣ routes/
 ┣ services/
 ┣ models/
 ┣ middlewares/
 ┣ utils/
 ┗ server.ts

🐳 Docker Support

Build Docker image:

npm run dockerize:dev

🤝 Contributing

Contributions are welcome!

Fork the project
Create your feature branch
Commit changes
Push to branch
Open Pull Request
📄 License

MIT License © 2026

⭐ Support

If you like this project, give it a star ⭐ on GitHub.
