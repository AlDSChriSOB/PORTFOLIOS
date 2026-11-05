# Christian Somtoo Obiechina — Professional Portfolio

Responsive portfolio for Data Science, AI and Machine Learning, research, analytics and quantitative finance.

## Automatic GitHub project sync

The project gallery reads public repositories directly from the GitHub REST API for [@AlDSChriSOB](https://github.com/AlDSChriSOB). Repository names, descriptions, languages, stars and links are populated at runtime. New public repositories are discovered automatically. Private repositories are not displayed.

## Publish with GitHub Pages

1. Open **Settings → Pages** in this repository.
2. Set **Build and deployment → Source** to **GitHub Actions**.
3. Push to `main`; the workflow in `.github/workflows/pages.yml` deploys the site.

Expected URL: https://aldschrisob.github.io/PORTFOLIOS/

## Updating the portfolio

- Update a repository README or description on GitHub; the gallery picks up the change through the API.
- Create a new public repository; it appears automatically.
- Edit `app.js` to change featured order or project categories.
- Edit `index.html` and `styles.css` to change content and design.

Built with HTML, CSS and vanilla JavaScript. No build step, database, API key or paid hosting is required. The site uses semantic landmarks, skip navigation, responsive layouts and reduced-motion support.
