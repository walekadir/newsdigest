Daily Digest — Nigerian Headlines
A lightweight, single-file web application that aggregates live news headlines from top Nigerian publications. It features a modern "dark mode" aesthetic, keyword-based categorization, and a resilient fetching system.

Key Features

Live Aggregation: Pulls real-time headlines from Punch, Vanguard, TechCabal, Premium Times, Channels TV, and Daily Post.

Smart Categorization: Automatically tags articles into Politics, Business, Tech, Sports, and Entertainment using a keyword-matching algorithm.

High Availability: Uses a "Proxy Waterfall" (CORS-anywhere, AllOrigins, etc.) to ensure the feed loads even if one proxy service is down.

Performance: Implements localStorage caching (30-minute TTL) to reduce API calls and improve load times.

Fully Responsive: Optimized for both desktop and mobile viewing with a "digital newspaper" feel.

Technical Architecture
The script is built using a "Vanilla" stack (no external frameworks required):

Frontend: HTML5, CSS3 (using Flexbox and Grid), and Google Fonts (Syne, DM Mono, Playfair Display).

Logic: JavaScript (ES6+).

Data Handling: XML DOMParser to convert RSS feeds into JSON objects.

State Management: Local storage handles the persistence of news items between refreshes.

How to Use
Save the file: Save the code as index.html.

Open in Browser: Simply double-click the file to run it locally, or host it on services like Vercel, Netlify, or GitHub Pages.

Interact:

Click "Refresh" to force a new fetch.

Use the Category Tabs to filter the feed by interest.

Click any headline to read the full story on the original publisher's website.

Dependencies
Fonts: Hosted by Google Fonts.

Proxies: Relies on public CORS proxies to bypass Cross-Origin Resource Sharing restrictions.
