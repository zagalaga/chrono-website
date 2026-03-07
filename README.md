# chrono.me - Local Website

A static local replica of [chrono.me](https://www.chrono.me), containing the same content, layout, and styling for offline viewing and development.

## Content Included

- **Hero**: The Unified Tracker for Every Life Metric
- **3 Steps**: Log Diverse Data → Find Hidden Connections → Guide Your Progress
- **Features**: Built-in Data Types, Custom Dashboard, Goals, Widgets, Custom Metrics, Data Ownership
- **Pricing**: Free and Pro plans
- **Blog**: Latest posts preview

## Project Structure

```
chrono-website/
├── index.html      # Main page
├── css/
│   └── styles.css  # Stylesheet
├── images/
│   └── favicon.png # Site favicon
├── js/
│   └── main.js     # Smooth scroll and interactions
└── README.md       # This file
```

## How to Run Locally

### Option 1: Python (built-in)

```bash
cd /Users/guytalmor/Workspace/chrono-website

# Python 3
python3 -m http.server 8000

# Then open http://localhost:8000 in your browser
```

### Option 2: Node.js (npx serve)

```bash
cd /Users/guytalmor/Workspace/chrono-website
npx serve

# Opens at http://localhost:3000 by default
```

### Option 3: Open directly

You can also open `index.html` directly in your browser. Some features (like smooth scrolling) work best when served over HTTP.

## Requirements

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No build step or dependencies required
