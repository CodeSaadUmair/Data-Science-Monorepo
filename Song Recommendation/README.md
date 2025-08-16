# 🎵 Content-Based Song Recommendation System

This project implements a **content-based song recommendation system** using **TF-IDF vectorization** and **cosine similarity**.  
It recommends songs based on their metadata (artist, genre) and lyrics similarity.

---

## 📌 Features
- Uses **TF-IDF (Term Frequency–Inverse Document Frequency)** to convert song metadata & lyrics into vectors.
- Computes **cosine similarity** between songs.
- Simple function `recommend_song(title, n)` to get top `n` similar songs.
- Easy to extend with larger datasets (CSV, Spotify API, etc.).

---

## 🛠️ Tech Stack
- Python 3
- [pandas](https://pandas.pydata.org/)
- [scikit-learn](https://scikit-learn.org/stable/)

---

## 📂 Project Structure
```
├── song_recommendation.ipynb   # Jupyter Notebook with implementation
├── README.md                   # Project documentation
```

---

## 🚀 Usage

1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook song_recommendation.ipynb
   ```
2. Run all cells.
3. Try recommending similar songs:
   ```python
   recommend_song("Shape of You", 3)
   ```

Example Output:
```
['Perfect', 'Despacito', 'Faded']
```

---

## 📊 Example Dataset
The notebook includes a **sample dataset** of 5 songs with:
- `title`
- `artist`
- `genre`
- `lyrics`

You can replace it with your own dataset in CSV/JSON format.

---

## 💡 Future Improvements
- Use **Spotify API** for real-world song data.
- Add **audio features (tempo, energy, danceability)**.
- Build a **Streamlit or Flask web app** for interactive recommendations.

---

## 👨‍💻 Author
Developed by [Bronil Koli](https://github.com/BronilKoli)
