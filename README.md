# 💎 DRUG GEM – FTIR Drug Identifier

**An AI-assisted spectral matching prototype for educational and research purposes.**

## 🔬 About the Project

DRUG GEM is a web-based application designed to analyse uploaded Infrared (IR) spectral data and find the closest matching compound from a reference spectral database.

The application uses spectral similarity matching to compare an uploaded spectrum against stored reference spectra and displays the closest match along with a similarity score and an interactive FTIR graph.

## ✨ Features

- **Spectrum Upload:** Upload spectral data in CSV format.
- **Spectral Analysis:** Compare uploaded data against reference spectra.
- **Compound Matching:** Display the closest matching reference compound.
- **Similarity Score:** Show the spectral similarity score.
- **Top Matches:** Display the five closest reference matches.
- **Interactive Graph:** Visualise the uploaded FTIR spectrum using Plotly.
- **User Interface:** Simple, interactive and responsive web design.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML | Website structure |
| Tailwind CSS | Styling and layout |
| JavaScript | Frontend functionality |
| Plotly.js | FTIR spectrum visualisation |
| Python | Backend processing |
| Flask | Backend API |
| Pandas & NumPy | Spectral data processing |

## ⚙️ How It Works

1. The user uploads a CSV file containing wavenumber and absorbance values.
2. The frontend sends the file to the Flask backend.
3. The backend processes the spectral data.
4. The uploaded spectrum is compared with stored reference spectra.
5. The application displays the closest reference match, similarity score, top matches and spectrum graph.

## 📊 Reference Dataset

The current backend contains 100 reference compound spectra.

The reference dataset is used for spectral similarity comparison. Compound labels are not all independently verified.

## 🌐 Project Deployment

- **Frontend:** GitHub Pages
- **Backend:** Flask API (currently tested locally; public hosting is planned).

## ⚠️ Important Disclaimer

DRUG GEM is an educational prototype, not a certified drug identification or forensic testing system.

A similarity score represents spectral resemblance, not the probability that a compound is present. Results must not be used for medical, legal, safety or law-enforcement decisions.

## 👩‍💻 Project Credits

**Developed by:** CU Students  
**Project Name:** DRUG GEM  
**Domain:** Artificial Intelligence | Spectral Analysis | Web Development

---

*Exploring the potential of AI-assisted spectral analysis.*
