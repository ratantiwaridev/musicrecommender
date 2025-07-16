# 🎵 Music Recommendation System

A content-based music recommendation system built with Python that suggests similar songs based on lyrics and textual features. This project demonstrates natural language processing, similarity measures, and interactive app deployment.

---

## 🚀 Features

- 📄 Input any song name and get a list of similar songs
- 🧠 Uses TF-IDF vectorization on song lyrics
- 📈 Cosine similarity-based recommendation engine
- 💡 Powered by pandas, scikit-learn, and Streamlit
- 🎧 Dataset from Spotify's Million Song Lyrics collection

---

## 📁 Project Structure

```
music-recommender/
├── app.py                   # Main app script (e.g., Streamlit UI)
├── training_model.ipynb     # Notebook for preprocessing and training
├── spotify_millsongdata.csv # Dataset (song name + lyrics)
├── requirements.txt         # Python dependencies
├── .gitignore               # Files to ignore in repo
└── README.md                # Project overview
```

---

## 📊 How It Works

1. **Preprocessing**:
   - Load song lyrics from CSV
   - Clean and transform text using TF-IDF

2. **Similarity Computation**:
   - Use cosine similarity to compare lyric vectors
   - Generate recommendations based on closest vectors

3. **App Interface**:
   - User inputs a song name
   - App returns a list of recommended similar songs

---

## 🛠️ Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/ratantiwaridev/musicrecommender.git
   cd musicrecommender
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the app:

   ```bash
   streamlit run app.py
   ```

---

## 📌 Requirements

- Python 3.8+
- pandas
- numpy
- scikit-learn
- streamlit

> See `requirements.txt` for the full list.

---

## 🗃️ Dataset Info

- **Source**: Spotify Million Song Lyrics Dataset
- **Content**: Song titles and full lyrics

> *Note*: Dataset is included for educational purposes only.

---

## 📷 Sample Output

_You can add screenshots here from your Streamlit UI if available._

---

## 🙌 Acknowledgements

- Spotify Million Song Dataset  
- Python, scikit-learn, Streamlit
