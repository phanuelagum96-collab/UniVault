UniVault 🎓

UniVault is a student learning platform that helps university students discover, share, and access educational resources such as lecture notes, past papers, tutorials, and learning materials.

🚀 Features

🔐 Student registration and authentication

📚 Upload and browse learning materials

🔎 Search and filter resources

📖 Course-based materials

🔖 Bookmark useful resources

⭐ Rate learning materials

🤖 Personalized recommendations

👤 Student profiles

🛠️ Admin management

📁 File uploads and storage

🧠 Machine-learning-based recommendations and classification

🛠️ Technology Stack
Frontend

Next.js

React

TypeScript

Tailwind CSS

Backend

Python

FastAPI

SQLAlchemy

Alembic

Database

The backend is designed to work with a relational database.

Machine Learning

Python

Content-based recommendation

Material classification

Text preprocessing

DevOps

Docker

Docker Compose

📁 Project Structure
UniVault/
│
├── README.md
├── .gitignore
├── docker-compose.yml
│
├── frontend/                 # Next.js + Tailwind CSS
│   ├── public/
│   └── src/
│       ├── app/
│       ├── components/
│       ├── lib/
│       ├── hooks/
│       ├── types/
│       └── config/
│
├── backend/                  # Python + FastAPI
│   ├── app/
│   │   ├── core/
│   │   ├── database/
│   │   ├── models/
│   │   ├── schemas/
│   │   ├── routers/
│   │   ├── services/
│   │   └── ml/
│   ├── migrations/
│   └── tests/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── storage/
│   └── uploads/
│
└── docs/
    ├── architecture.md
    ├── database_schema.md
    └── machine_learning.md

⚙️ Getting Started
Prerequisites

Make sure you have installed:

Node.js

npm

Python 3.10+

Docker

Git

Clone the Repository
git clone https://github.com/phanuelagum96-collab/UniVault.git
cd UniVault

💻 Frontend Setup

Go to the frontend directory:

cd frontend


Install dependencies:

npm install


Create your environment file:

cp .env.local.example .env.local


Start the development server:

npm run dev


The frontend will be available at:

http://localhost:3000

🐍 Backend Setup

Open a new terminal and go to the backend:

cd backend


Create a virtual environment:

python -m venv venv


Activate it on Linux/macOS:

source venv/bin/activate


On Windows:

venv\Scripts\activate


Install dependencies:

pip install -r requirements.txt


Create your environment file:

cp .env.example .env


Start the FastAPI server:

uvicorn app.main:app --reload


The API will be available at:

http://localhost:8000


API documentation:

http://localhost:8000/docs

🐳 Running with Docker

You can run the project using Docker Compose:

docker compose up --build


To stop the containers:

docker compose down

🧠 Machine Learning

UniVault includes machine-learning functionality for improving resource discovery and recommendations.

The ML system includes:

Text preprocessing

Dataset preparation

Content-based recommendations

Educational material classification

Model training

Model evaluation

Model inference

ML-related code is located in:

backend/app/ml/

📚 Documentation

Additional technical documentation is available in the docs/ directory:

architecture.md — System architecture

database_schema.md — Database design

machine_learning.md — Machine-learning system

🤝 Contributing

Contributions are welcome!

Please read CONTRIBUTING.md before contributing to the project.

📜 Code of Conduct

Please read CODE_OF_CONDUCT.md to understand the standards expected from contributors and community members.

🔐 Security

Do not commit sensitive information such as:

Passwords

API keys

Database credentials

Secret tokens

.env files containing secrets

Use the provided .env.example files as templates for environment configuration.

🎓 Academic Integrity

UniVault is designed to support learning and responsible academic collaboration.

Users should respect:

Copyright

Intellectual property

University policies

Academic integrity

Only upload educational materials that you have permission to share.

📄 License

This project is currently under development.

License information will be added when the project license is finalized.

👨‍💻 Author

Phanuel Agum

GitHub: @phanuelagum96-collab

⭐ UniVault — Learn. Share. Discover.
