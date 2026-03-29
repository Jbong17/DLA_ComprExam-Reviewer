# DLA Comprehensive Exam Reviewer
### Deep Learning Algorithms · PhD in Data Science 2028 · AIM

A web-based 6-day study reviewer with progress tracking, linked to Jupyter notebooks
hosted on this repository. Mirrors the ATSA Comprehensive Reviewer format.

---

## 📂 Repository Structure

```
DLA-PhD-DS-2028/
├── index.html                                    ← Web reviewer (deploy this)
├── README.md
├── DLA_Notebook1_Neural_Networks.ipynb
├── DLA_Notebook2_CNN.ipynb
├── DLA_Notebook3_RNN_LSTM.ipynb
├── DLA_Notebook4_Detection_Segmentation.ipynb
├── DLA_Notebook5_Representation_Learning.ipynb
└── DLA_Notebook6_Generative_Models.ipynb
```

---

## 🚀 Deployment (GitHub Pages — 5 minutes)

### Step 1 — Create the repository
1. Go to [github.com/new](https://github.com/new)
2. Name it exactly: `DLA-PhD-DS-2028`
3. Set to **Public** (required for GitHub Pages + Colab links)
4. Click **Create repository**

### Step 2 — Upload files
Upload all files in this folder:
- `index.html`
- `README.md`
- All 6 `.ipynb` notebook files

### Step 3 — Configure GitHub Pages
1. Go to your repo → **Settings** → **Pages**
2. Under *Source*, select **Deploy from a branch**
3. Branch: `main` · Folder: `/ (root)`
4. Click **Save**

Your reviewer will be live at:
```
https://YOUR_USERNAME.github.io/DLA-PhD-DS-2028/
```

### Step 4 — Update the reviewer URL
Open `index.html` and change lines 4–5:
```js
const GITHUB_USER = 'YOUR_USERNAME';   // ← replace with your GitHub username
const GITHUB_REPO = 'DLA-PhD-DS-2028'; // ← keep this or change to your repo name
```

---

## 🔗 How Links Work

| Button | URL pattern |
|---|---|
| **Open in Colab** | `colab.research.google.com/github/USER/REPO/blob/main/NOTEBOOK.ipynb` |
| **Download .ipynb** | `raw.githubusercontent.com/USER/REPO/main/NOTEBOOK.ipynb` |

Both are generated automatically from the `GITHUB_USER` and `GITHUB_REPO` constants.

---

## ✅ Features

- **Progress tracking** — checkboxes per topic, saved to `localStorage`
- **Day rings** — circular progress indicator per session
- **Global bar** — 0/43 topics tracked across all 6 days
- **Open in Colab** — one click to launch any notebook in Google Colab
- **Download .ipynb** — direct file download from GitHub raw
- **Expand/Collapse All** — floating action button
- **Reset progress** — clears all localStorage state
- **Responsive** — works on mobile and desktop
- **No dependencies** — pure HTML/CSS/JS, no build step

---

## 📚 Notebook Coverage

| Day | Notebook | Sessions | Topics |
|---|---|---|---|
| 1 | Neural Networks — Fundamentals & Applications | 1–7 | 7 |
| 2 | Convolutional Neural Networks (CNN) | 8–11 | 7 |
| 3 | Recurrent Neural Networks & LSTM | 12–13 | 7 |
| 4 | Object Detection & Segmentation | 14–15 | 7 |
| 5 | Representation Learning | 16 | 7 |
| 6 | Generative Models — VAE & GAN | 17 | 8 |

**Total: 43 reviewable topics**

---

## 🛠 Local Development

No build tool needed. Just open `index.html` in a browser:

```bash
# Option 1: direct file open
open index.html

# Option 2: local server (avoids CORS issues with font loading)
python3 -m http.server 8080
# then visit http://localhost:8080
```

---

*AIM · Aboitiz School of Innovation, Technology and Entrepreneurship (ASITE)*
*Prof. Christopher P. Monterola & Prof. Daniel Stanley Tan, PhD*
