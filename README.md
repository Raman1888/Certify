# Certify
A project that uses AI and blockchain technology inorder to provide skills and on chain certifications to students. Employers can also recruit them seeing their progress.

🚀 Features
AI-Generated Career Roadmaps – Personalized career paths based on skills, qualifications, and aspirations.
Blockchain-Based Skill Passport – Immutable, verifiable records of learning achievements.
Live Resume/Portfolio – Shareable career progress with recruiters.
Recruiter Job Posting & Candidate Selection – Employers can post jobs and select candidates.
Secure Authentication & Data Hashing – User authentication with blockchain-backed data security.

🛠️ Tech Stack
Backend:
Flask
Flask-SQLAlchemy
Blockchain (hashed data storage & retrieval)
Frontend:
Tailwind CSS
HTML
JavaScript
Database:
PostgreSQL / MySQL (using Flask-SQLAlchemy ORM)
🔧 Installation Instructions
1️⃣ Clone the Repository
 git clone https://github.com/your-repo/certify.git
 cd certify
2️⃣ Set Up a Virtual Environment
 python -m venv venv
 source venv/bin/activate  # On Windows use: venv\Scripts\activate
3️⃣ Install Dependencies
 pip install -r requirements.txt
4️⃣ Configure Environment Variables
Create a .env file and add necessary credentials:

Copy to BlackBox
SECRET_KEY=your_secret_key
DATABASE_URL=your_database_url
BLOCKCHAIN_NODE=your_blockchain_node
5️⃣ Run the Flask App
 python main.py

📂 Directory Structure
Copy to BlackBox
certify/
│── static/               # Static assets (CSS, JS, images)
│── templates/            # HTML templates
│── auth.py               # Authentication routes
│── models.py             # Database models (Flask-SQLAlchemy)
│── routes.py             # Core application routes
│── blockchain.py         # Blockchain integration logic
│── main.py               # App setup and execution
│── requirements.txt      # Project dependencies
│── .env                  # Environment variables
│── README.md             # Project documentation

🔍 How It Works
For Candidates:
Sign Up/Login – Authenticate using email and password.
Enter Qualifications & Skills – Helps AI generate a personalized roadmap.
Follow AI-Powered Career Roadmap – Progress through suggested courses and experiences.
Earn Blockchain-Verified Certificates – Completed milestones are stored on the blockchain.
Share Resume with Recruiters – Verifiable, tamper-proof resumes help in job applications.

For Recruiters:
Sign Up/Login – Authenticate as a recruiter.
Post Job Listings – Define roles and required candidate criteria.
Browse Candidates – Select and contact suitable candidates.
Pay for Candidate Access – Recruiters pay to access candidate details.
📖 Usage Guide
Register as a Candidate or Recruiter.
Candidates: Enter details, follow AI-generated career plans, build a blockchain-based resume.
Recruiters: Post jobs, browse candidates, and access profiles.
Secure Resume Sharing: Candidates share their blockchain-verified profile link with recruiters.

🚀 Future Scope
AI-Powered Job Matching – Automate candidate-job matching.
Integrated Chat System – Direct recruiter-candidate interaction.
NFT-Based Certificates – Digital proof-of-skill ownership.
Industry-Specific Learning Tracks – Custom AI learning paths for different industries.

👥 Contributing
We welcome contributions! To contribute:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Commit changes (git commit -m "Added new feature").
Push to your branch (git push origin feature-branch).
Submit a pull request.
