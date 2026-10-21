# Chapter 11: Separating Techniques — Interactive Visual Scrubber Lab

An interactive, visual educational web application exploring physical separation techniques, grounded in **Exploring Science — Chapter 11: Separating Techniques** (Pages 117–122).

Developed by **Prasad k**.

---

## 🔬 Features

1. **Scrubber Motion Lab**:
   - High-fidelity interactive canvas animations with real-time scrubber timeline (0–100%).
   - All 4 separation techniques covered:
     - **Evaporation** (Page 117)
     - **Crystallisation** (Page 118)
     - **Sublimation** (Page 119)
     - **Simple Distillation** (Page 120)
   - Real-time particle magnifier lens showing molecular/ionic movement.
   - Interactive apparatus inspector and real-world connection highlights.
   - Comprehensive summary comparison matrix.

2. **Mixture Solver & Activity 11.1**:
   - 3-step interactive challenge to separate sand, water, and salt.
   - Essential lab safety precautions checklist.
   - Critical thinking scenarios (kerosene/petrol, survival seawater distillation).
   - End-of-unit Question 8 mixture classifier.

3. **Purification in the Real World & Pioneers (11.2)**:
   - Real-world applications across medicine, food, and industry.
   - 8-profession interactive explorer (Activity 11.2).
   - Historical contributions of classical Muslim chemists (Jabir ibn Hayyan, Al-Kindi, Al-Razi).

4. **Chapter Quiz (11.3)**:
   - 8 interactive multiple-choice questions with instant scoring, feedback, and textbook page citations.

---

## 🚀 How to Publish to GitHub Pages

This project is a standalone, client-side web application ready for instant deployment to GitHub Pages without any build steps.

### Step 1: Initialize Git and Commit
Open PowerShell or your terminal in this folder and run:

```bash
git init
git add .
git commit -m "Initial commit: Chapter 11 Separating Techniques Lab"
git branch -M main
```

### Step 2: Create a New GitHub Repository
1. Go to [github.com/new](https://github.com/new).
2. Name your repository (for example: `separating-techniques-lab`).
3. Leave it Public (or Private if you have GitHub Pro).
4. Do **not** initialize with README, .gitignore, or license (we already have them).
5. Click **Create repository**.

### Step 3: Link and Push to GitHub
Copy the remote URL from your new GitHub repo and run:

```bash
git remote add origin https://github.com/<YOUR_GITHUB_USERNAME>/separating-techniques-lab.git
git push -u origin main
```

*(Replace `<YOUR_GITHUB_USERNAME>` with your actual GitHub username)*

### Step 4: Enable GitHub Pages
1. Go to your repository on GitHub.
2. Click **Settings** (top tab) ➔ **Pages** (left sidebar).
3. Under **Build and deployment**:
   - **Source**: Select **Deploy from a branch**.
   - **Branch**: Select `main` and folder `/ (root)`.
   - Click **Save**.
4. In about 30–60 seconds, your site will be live at:
   ```
   https://<YOUR_GITHUB_USERNAME>.github.io/separating-techniques-lab/
   ```

*(Alternatively, under Source you can select **GitHub Actions** and the included `.github/workflows/deploy.yml` workflow will automatically deploy it).*

---

## 💻 Local Preview

To run and preview the website on your local machine:

### Option A: Using Node.js (Included)
```bash
node serve.cjs
```
Then open your browser to [http://localhost:3000](http://localhost:3000).

### Option B: Using Python
```bash
python -m http.server 3000
```
Then open your browser to [http://localhost:3000](http://localhost:3000).

### Option C: Directly in Browser
You can also directly double-click `index.html` to open it in any modern web browser (Chrome, Edge, Firefox, Safari).
