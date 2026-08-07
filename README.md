# Kashika .data - Portfolio Website

A single-page, data-driven portfolio site showcasing my work in data science, machine learning, and analytics built to let recruiters and collaborators explore live, working projects rather than just read about them.

**🔗 Live site:** [kashika3006.github.io/kashika-portfolio-website](https://kashika3006.github.io/kashika-portfolio-website/)

---

## Overview

This portfolio is built as a single self-contained HTML file with a dark theme and cyan/purple accents, featuring an animated network canvas background. All content: projects, skills, certifications, experience, and education is driven by a single JavaScript `DATA` object, making the site easy to update without touching layout or styling code.

## Features

- **Expandable project cards** - click into any project for a full overview, highlights, and key metrics, without leaving the page
- **Filterable project grid** - filter by category (Machine Learning, Analytics, etc.)
- **Certifications gallery** - view completed credentials with links to verify certificates
- **Experience & education timelines** - chronological view of internships and academic background
- **Animated canvas background** - a subtle, connected-node network effect that runs behind all sections
- **Fully responsive** - adapts to mobile and tablet breakpoints

## Tech Stack

- **HTML5 / CSS3** - custom properties (CSS variables) for theming, CSS Grid for layout
- **Vanilla JavaScript** - no frameworks; DOM rendering driven by a central `DATA` object
- **Canvas API** - for the animated background

## Projects Featured

| Project | Stack | Highlights |
|---|---|---|
| Personalized Book Recommendation Engine | Python, Scikit-learn, Pandas, Streamlit | TF-IDF vs. SVD comparison on ~982K Goodreads ratings |
| Wine Quality Prediction | Python, MLflow, Flask, Render | End-to-end tracked and deployed ML pipeline |
| Retail Sales Data Cleaning & Analysis | Python, Pandas, Power BI | Cleaned dataset → interactive BI dashboard |

*(See the live site for full details, live demos, and source links for each project.)*

## Project Structure

```
kashika-portfolio-website/
├── index.html      # Single-file site: markup, styles, and DATA object
├── certs/          # certificates images
└── README.md       
```

## Running Locally

Since this is a single static HTML file, no build step is required:

```bash
git clone https://github.com/kashika3006/kashika-portfolio-website.git
cd kashika-portfolio-website
```

Then simply open `index.html` in your browser, or serve it locally:

```bash
python -m http.server 8000
```

and visit `http://localhost:8000`.

## Contact

- **LinkedIn:** linkedin.com/in/kashika-b8813222b
- **Email:** kashika3006@gmail.com
- **Portfolio:** [kashika3006.github.io/kashika-portfolio-website](https://kashika3006.github.io/kashika-portfolio-website/)

---

*Built and maintained by Kashika - BCA student at IGNOU, New Delhi.*
