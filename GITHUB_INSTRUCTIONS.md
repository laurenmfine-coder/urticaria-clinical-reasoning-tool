# 🚀 GitHub Deployment Instructions

## Quick Start (5 Minutes)

### Step 1: Create Repository

1. Go to [github.com/new](https://github.com/new)
2. Fill in:
   - **Repository name:** `urticaria-clinical-reasoning-tool`
   - **Description:** Evidence-based chronic urticaria learning tool with gamified quizzes
   - **Visibility:** Public (recommended for educational resources)
   - ✅ Check "Add a README file" (we'll replace it)
3. Click **Create repository**

### Step 2: Upload Files

1. In your new repository, click **Add file** → **Upload files**
2. Drag and drop the **entire contents** of the `urticaria_tool` folder:
   - `README.md`
   - `game/` folder
   - `evidence_summaries/` folder
   - `tables/` folder
   - `pearls/` folder
   - `cases/` folder
   - `quizzes/` folder
   - `flashcards/` folder
   - `algorithms/` folder
3. Add commit message: `Initial commit: Complete urticaria learning tool`
4. Click **Commit changes**

### Step 3: Enable GitHub Pages (for the interactive game)

1. Go to **Settings** tab (top of repository page)
2. Click **Pages** in the left sidebar
3. Under "Branch," select **main** from dropdown
4. Click **Save**
5. Wait 2-3 minutes for deployment

### Step 4: Get Your URLs

Your repository will be available at:
```
https://github.com/YOUR-USERNAME/urticaria-clinical-reasoning-tool
```

The interactive game will be playable at:
```
https://YOUR-USERNAME.github.io/urticaria-clinical-reasoning-tool/game/urticaria-challenge.html
```

---

## File Checklist

Before uploading, verify you have all these files:

```
urticaria_tool/
├── ✅ index.html (Landing Page)
├── ✅ README.md
├── ✅ game/
│   ├── urticaria-challenge.html
│   └── urticaria-compendium.html
├── ✅ evidence_summaries/
│   └── JTFPP_systematic_reviews_integrated.md
├── ✅ tables/
│   └── treatment_comparison_tables.md
├── ✅ pearls/
│   └── clinical_pearls_integrated.md
├── ✅ cases/
│   └── clinical_cases_integrated.md
├── ✅ quizzes/
│   └── quiz_bank_integrated.md
├── ✅ flashcards/
│   └── flashcards_integrated.md
└── ✅ algorithms/
    └── treatment_algorithm_2025.md
```

---

## Sharing the Tool

### Share the Landing Page (Main Entry Point)
```
https://YOUR-USERNAME.github.io/urticaria-clinical-reasoning-tool/
```

### Share the Game Directly
```
https://YOUR-USERNAME.github.io/urticaria-clinical-reasoning-tool/game/urticaria-challenge.html
```

### Share the Compendium Directly
```
https://YOUR-USERNAME.github.io/urticaria-clinical-reasoning-tool/game/urticaria-compendium.html
```

### Embed in Substack
In your Substack post, add a button or link:
```markdown
[🎮 Play the Urticaria Challenge](https://YOUR-USERNAME.github.io/urticaria-clinical-reasoning-tool/game/urticaria-challenge.html)
```

### Share on LinkedIn
```
🩺 New educational resource: Chronic Urticaria Clinical Reasoning Tool

Built from 4 AAAAI/ACAAI systematic reviews (158 studies, 16,000 participants)

Features:
🎮 Gamified quiz with XP, badges & leaderboards
📊 Evidence-based treatment rankings
💊 NNT/NNH for clinical counseling
🔬 Emerging therapies coverage

Try it: [YOUR LINK]

#MedEd #Allergy #Dermatology #EvidenceBasedMedicine
```

---

## Updating Content

To update files after initial upload:

1. Navigate to the file in your repository
2. Click the **pencil icon** (Edit)
3. Make changes
4. Add commit message describing the update
5. Click **Commit changes**

Or upload a new version:
1. Click **Add file** → **Upload files**
2. Upload the updated file (same name = replaces old version)
3. Commit changes

---

## Troubleshooting

### Game not loading?
- Wait 2-3 minutes after enabling GitHub Pages
- Make sure the file path is exactly: `game/urticaria-challenge.html`
- Try clearing browser cache

### README not displaying correctly?
- GitHub renders Markdown automatically
- Make sure the file is named exactly `README.md` (case-sensitive)

### Files in wrong location?
- Repository root should contain `README.md` and folders directly
- Don't nest everything inside another folder

---

## Optional: Custom Domain

If you want a custom URL like `urticaria-tool.yourdomain.com`:

1. Go to Settings → Pages
2. Under "Custom domain," enter your domain
3. Follow GitHub's DNS configuration instructions
4. Wait for SSL certificate (can take up to 24 hours)

---

*Ready to share your educational resource with the world!*
