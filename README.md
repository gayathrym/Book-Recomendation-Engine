#NEXTPAGE - Book Reccommendation Engine
![Python](https://img.shields.io/badge/Backend-Python-blue)
![JavaScript](https://img.shields.io/badge/Frontend-JavaScript-yellow)
![Tailwind CSS](https://img.shields.io/badge/Styling-TailwindCSS-38B2AC)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

NextPage is a fast, personalized web app that helps you find books you’ll actually love.
Built with a Python backend and a clean React frontend, it delivers smart recommendations based on your ratings and reading preferences.
Search, explore, rate, and stack your next reads—all in one place


Features

Frontend
Home page for guests with genre discovery and tagline
Personalized home page for logged-in users with recommendations
Book cards with cover, title, author, ratings, and add-to-shelf option
Detailed book pages with shelving, rating, reviewing, and community reviews
User profile with avatar, stats, ratings, bookshelves (To-Read, Finished), and reviews
Search and filter books by genre, year, rating, and author
Grid/List view toggle for search results
Recommendation page with clickable book suggestions

Backend
Loads and preprocesses book data from CSV
Vectorizes book content using TF-IDF
Calculates cosine similarity to recommend similar books
Recommends books based on title input
Saves trained recommendation model using joblib
Integrated with the frontend to serve live recommendations

Demo:


https://github.com/user-attachments/assets/a0176a85-d381-49c0-8b96-e98d803d18b5


https://github.com/user-attachments/assets/274633ba-005e-4c5e-9ebf-3ee80c9facaf


https://github.com/user-attachments/assets/be213119-459d-43d8-8848-91b71886bf2f


Project Structure
project/
│
├── src/                  # React Frontend
│
├── backend/              # Python Backend
│   ├── recommender.py
│   ├── Book_Details.csv
│   └── book_recommender.pkl
│
└── README.md


Installation -
Backend

cd backend
pip install pandas scikit-learn joblib
python recommender.py
The trained model will be saved as book_recommender.pkl.

Frontend

cd src
npm install
npm run dev


Usage
Visit the live site.

Sign up and log in to access personalized features.

Rate a few books you’ve read.

Get book recommendations tailored to your preferences.

Search, explore, and track your reading lists and reviews.

Security Notes
User data is handled securely in the deployed version.

The application currently does not use advanced authentication or encryption layers.

Further security and scalability improvements can be added in future versions.

License
This project is licensed under the MIT License.
