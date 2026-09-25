# PPQ Cost Analyzer

A small, client-side HTML tool for analyzing PPQ CSV exports and summarizing model usage and cost.

## Features

- Upload a CSV file by drag-and-drop or file picker.
- Analyze total cost, requests, input tokens, and daily cost.
- View cost and request summaries by model and date.
- Click any table column heading to sort ascending or descending.
- Ignores the summary rows appended to the end of PPQ CSV exports, such as `Total Records`, `Total Input Tokens`, `Total Output Tokens`, and `Total Cost (USD)`.
- Responsive layout for phones and tablets, while keeping tables horizontally scrollable when needed.
- Runs entirely in the browser; CSV data is not uploaded to a server.

## Usage

Open `index.html` in a modern web browser and select a compatible CSV export.

## GitHub Pages

This repository can be published directly with GitHub Pages.

1. Push the files to the branch used by GitHub Pages.
2. Open the repository on GitHub and go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the publishing branch and the `/ (root)` folder.
5. Click **Save**.
6. GitHub will publish `index.html` as the site's start page.

## Suggested commit messages

- `fix: ignore CSV summary rows in analyzer`
- `style: improve mobile layout`
- `docs: update README for CSV summary handling and mobile support`
- `refactor: use index.html as GitHub Pages entry point`
