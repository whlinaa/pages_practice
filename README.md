# Finance Analysis 101 (GitHub Pages Project)

A lightweight multi-page educational website that introduces core stock analysis metrics for beginners.

## Project Goals

- Explain important risk-adjusted return metrics in plain language.
- Provide a clear learning path across multiple pages.
- Keep everything static (HTML/CSS) so it is easy to host on GitHub Pages.

## Site Structure

- `index.html` — Home page and learning overview
- `metrics/sharpe-ratio.html` — Sharpe Ratio basics
- `metrics/information-ratio.html` — Information Ratio basics
- `metrics/volatility-and-beta.html` — Volatility and Beta primer
- `styles.css` — Shared styling across all pages

## What You Will Learn

1. **Sharpe Ratio**  
	How to compare return per unit of total risk.

2. **Information Ratio**  
	How to evaluate active return vs. a benchmark with consistency.

3. **Volatility & Beta**  
	How to separate standalone price fluctuation from market sensitivity.

## Run Locally

Because this is a static site, you can just open `index.html` in your browser.

For a better local dev experience (recommended), use VS Code Live Server or any static server.

## Deploy to GitHub Pages

1. Push this project to a GitHub repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose:
	- **Source**: Deploy from a branch
	- **Branch**: `main` (or your default branch), `/ (root)`
4. Save and wait for deployment.
5. Open your published URL.

## Notes

- This project is for education only.
- Content is not financial advice.
- You can extend it by adding pages for metrics like Sortino Ratio, Max Drawdown, and Alpha.
