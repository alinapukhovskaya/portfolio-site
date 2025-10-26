===============================================
MBA Portfolio – Quarto Project
Author: Alina Pukhovskaya, MBA, PhD
===============================================

FILES INCLUDED
--------------
1. alina_portfolio.qmd   - Main Quarto Markdown file with all portfolio content
2. styles.css            - Custom stylesheet for clean, professional design
3. (Optional) images/    - Place your headshot here (images/alina-headshot.jpg)


INSTRUCTIONS
-------------
1. Install Quarto if not already:
   https://quarto.org/docs/get-started/

2. Open the project folder in VS Code.

3. Preview your portfolio:
   quarto preview alina_portfolio.qmd

   - This opens a live HTML preview in your browser.
   - The Table of Contents appears on the right.
   - Changes in the .qmd file refresh automatically.

4. Export to PDF or HTML:
   quarto render alina_portfolio.qmd --to html
   quarto render alina_portfolio.qmd --to pdf   (requires LaTeX)

5. Optional customization:
   - Add a professional headshot to images/alina-headshot.jpg
   - Adjust the primary accent color in styles.css (variable: --accent)
   - Replace or add your logo in the title section of the .qmd

6. Suggested colors (inspired by alinapukhovskaya.com):
   - Accent Blue: #2a6fff
   - Neutral Gray: #6b7280
   - Background: #ffffff
   - Text: #1f2a37


FOLDER STRUCTURE
----------------
portfolio_quarto/
│
├── alina_portfolio.qmd
├── styles.css
├── README.txt
└── images/
    └── alina-headshot.jpg (optional)


NOTES
-----
- Designed for a one-page MBA student portfolio.
- Compatible with Quarto, VS Code, and RStudio.
- Ideal for academic or career use (e.g., e-portfolios, online resumes, or showcase sites).
