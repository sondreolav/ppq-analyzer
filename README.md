# PPQ Cost Analyzer

A small, client-side HTML tool for analyzing PPQ CSV exports and summarizing model usage and cost.

## Features

- Upload a CSV file by drag-and-drop or file picker.
- Analyze total cost, requests, input tokens, and daily cost.
- View cost and request summaries by model and date.
- Click any table column heading to sort ascending or descending.
- Highlights a few useful anomalies, such as free requests, large contexts, and requests with zero tokens.
- Runs entirely in the browser; the CSV data is not uploaded to a server.

## Usage

Open `ppq-analyzer.html` in a modern web browser and select a compatible CSV export.

## Notes

The analyzer expects CSV fields such as `Model`, `Date`, `Time`, `Price (USD)`, `Input Tokens`, and `Output Tokens`.
