#  Movie Recommendation System

A Flask-based movie recommendation system that suggests movies based on user preferences. This project provides personalized recommendations using similarity data and integrates external APIs to enhance movie details.


##  Features

*  User authentication (Login & Register)
*  Search movies by name
*  Personalized movie recommendations
*  Movie details (poster, rating, overview, cast)
*  TMDb API integration for real-time data
*  Simple UI using HTML, CSS

##  Tech Stack

* Python
* Flask
* Pandas, NumPy
* Pickle (for model storage)
* TMDb API
* HTML, CSS

##  Project Structure

```
project/

├── app.py
├── data_setup.py
├── model_builder.py
├── preload_posters_genres.py
├── movies.db

├── templates/
├── static/
├── data/

├── .gitignore
└── README.md
```

##  How It Works

* The system uses a similarity matrix to recommend movies similar to the selected one.
* Movie details and posters are fetched using the TMDb API.
* User authentication is handled securely using hashed passwords.

---

##  Setup Instructions

1. Clone the repository:
   git clone https://github.com/your-username/Movie-Recommendation-System.git
   cd Movie-Recommendation-System

2. Install dependencies:
   pip install -r requirements.txt

3. Add your TMDb API key in app.py:
   API_KEY = "your_api_key_here"

4. Run the application:
   python app.py

5. Open in browser:
   http://127.0.0.1:5000/

---

##  Note

* Large files like .pkl (model & similarity data) are not included due to GitHub size limits.
* You can generate them using the provided scripts or add them manually to the data/ folder.


##  Future Improvements

* Add collaborative filtering
* Improve UI design
* Deploy the application online
* Add user-based recommendations

---

##  Author

Gokila Krishna B
B.Tech – Artificial Intelligence & Machine Learning  

Interested in AI, Machine Learning, and Full Stack Development.  
Focused on building practical and user-friendly applications.

---

##  License

This project is licensed under the MIT License. 
<img width="1280" height="720" alt="WhatsApp Image 2026-05-17 at 12 59" src="https://github.com/user-attachments/assets/cd77102a-84f6-492a-9ee4-0fa78a85e17f" />
<img width="1280" height="670" alt="WhatsApp Image 2026-05-17 at 12 59 34" src="https://github.com/user-attachments/assets/704e4719-323c-497a-b2e4-526a6a4bc86d" />

