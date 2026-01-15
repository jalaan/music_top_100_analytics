#  Music Top 100 Analytics Dashboard

An interactive, production-style analytics dashboard built with **Next.js**, **TypeScript**, and **React Server + Client Components**.  
This project analyzes Spotify Top 100 streaming data and presents it through KPI metrics, interactive visualizations, and URL-driven state management.

![Dashboard Overview](screenshots/dashboard-overview.png)

---

##  Project Overview

This dashboard simulates a real-world **decision intelligence product**, similar to what an analytics engineer or data product analyst would build for leadership, content strategy, or growth teams.

It enables users to:
- Analyze top artists by total streams
- Drill into individual artists
- Filter and search tracks dynamically
- Sort results across multiple dimensions
- Share exact dashboard views via URL

---

## Key Features

### KPI Metrics
- Total Tracks
- Unique Artists
- Total Streams (formatted at scale)

### Interactive Analytics
- **Artist drill-down** via clickable bar chart
- **Dynamic track filtering** by artist and search query
- **Sortable tables** (track, artist, streams)
- **Graceful empty-state handling**

### Advanced UX
- URL-synced state (`artist`, `search`, `sort`, `direction`)
- Shareable dashboard views
- Client/server separation using Next.js App Router

---

## Example Interactions

### Artist Drill-Down
![Artist Drilldown](screenshots/artist-drilldown.png)

### Search + Filter
![Search Filter](screenshots/search-filter.png)

### Empty State Handling
![Empty State](screenshots/empty-state.png)

---

## Tech Stack

- **Next.js 16 (App Router)**
- **TypeScript**
- **React Server & Client Components**
- **Custom API Routes**
- **CSV → JSON data processing**
- **Inline D3-style visual rendering**
- **URL-based state management**

---

## API Design

The dashboard is powered by a custom API endpoint:
Which returns:
- Aggregated KPI metrics
- Top artists by total streams
- Top tracks with artist attribution

Example API response:

![API Response](screenshots/api-response.png)

---

## Project Structure

![Project Structure](screenshots/project-structure.png)

---

## Why This Project Matters

This project demonstrates:
- Analytics engineering fundamentals
- Product-oriented data thinking
- UX considerations for data products
- Real-world dashboard architecture
- Clean separation of concerns

It mirrors the internal tooling used by companies like Netflix, Spotify, Amazon, and Meta.
—-

## Data Source

Spotify Top 100 dataset sourced from **Kaggle** and transformed for analytics use.
---

## Author

**Jalaan Fields**  
 Analytics Engineer  
