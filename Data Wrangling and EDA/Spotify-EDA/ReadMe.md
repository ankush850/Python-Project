# Spotify Favorite Artists: Exploratory & Explanatory Data Analysis

## 📌 Project Overview
This project explores audio features and popularity trends across **17 major global music artists** extracted via the **Spotify Web API** using the `spotipy` Python library.

The study investigates how musical characteristics like energy, danceability, valence (musical positiveness), loudness, tempo, and key signatures impact track popularity and differentiate artist genres (Pop, Rock, Hip-Hop, EDM, Reggae).

---

## 🎤 Analyzed Artists
*Ed Sheeran, Shawn Mendes, Calvin Harris, Justin Bieber, Charlie Puth, Martin Garrix, The Chainsmokers, Alan Walker, Dua Lipa, Bruno Mars, AC/DC, Kanye West, Guns N' Roses, Green Day, The Weeknd, Eminem, Bob Marley & The Wailers.*

---

## 📊 Dataset & Extracted Features
- **`df_original.csv` / `original_df.csv`**: Contains tracks with extracted audio features:
  - `danceability`, `energy`, `key`, `loudness`, `mode`, `speechiness`
  - `acousticness`, `instrumentalness`, `liveness`, `valence`, `tempo`, `duration_ms`, `popularity`

---

## 💡 Key Analysis & Conclusions
1. **Energy vs. Loudness & Valence**:
   - High positive correlation between track energy and loudness.
   - Danceable songs correlate with higher valence (happier, positive feel). Bob Marley & The Wailers scored highest in valence and danceability.
2. **Liveness & Genres**:
   - Rock bands (AC/DC, Green Day) and rappers (Eminem, Kanye West) show higher liveness compared to pop artists.
3. **Popularity**:
   - Eminem's "Mockingbird" scored peak individual popularity (88/100).
   - Kanye West and The Weeknd boast the highest number of top-tier popular albums.
4. **Song Duration & Tempo**:
   - Average song duration concentrates between 3.0 to 4.5 minutes.
   - Fast and moderate tempos dominate over slow ballads.
5. **Key & Time Signature**:
   - $4/4$ time signature is overwhelmingly the most common ($\approx 95\%$). Keys $C\#$ and $D$ are the most frequently used by popular songwriters.

---

## 📦 Requirements & Installation
Install dependencies:

```bash
pip install -r requirements.txt
```

### Dependencies
- `pandas` - Tabular data manipulation
- `numpy` - Numerical statistics
- `spotipy` - Spotify Web API integration
- `pywaffle` - Waffle chart visualizations for categorical breakdowns
- `seaborn` & `matplotlib` - Distribution, correlation, and multivariate plots
- `jupyter` / `notebook` - Notebook environment

---

## 🚀 How to Run
Open and run the main analysis notebook:

```bash
jupyter notebook "My_Favorite_Artists _Spotify_Data_Exploration.ipynb"
```
