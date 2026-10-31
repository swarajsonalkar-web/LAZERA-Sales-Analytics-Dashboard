# LAZERA — Sales Analytics Dashboard

A business intelligence dashboard designed to import sales data and generate meaningful sales performance summaries.

**Built by Swaraj Sonalkar**

## Overview

LAZERA is a sales analytics platform that helps users understand business performance through structured sales records.

Users can import CSV files containing transaction data and view revenue, order counts, product performance, and monthly summaries.

## Features

- CSV data importing
- Sales record storage
- Revenue calculation
- Total order tracking
- Unit sales calculation
- Monthly revenue summaries
- Product-wise revenue analysis
- Interactive dashboard
- SQLite database integration

## Technology Stack

| Technology | Purpose |
|---|---|
| Node.js | Runtime |
| Express.js | Backend |
| SQLite | Database |
| Better-SQLite3 | Database integration |
| CSV Parse | CSV processing |
| HTML5 | Structure |
| CSS3 | Styling |
| JavaScript | Dashboard functionality |

## CSV Format

The application expects the following columns:

```csv
date,product,quantity,amount
2026-01-04,Notebook,4,800
2026-01-12,Pen Set,8,400
2026-02-03,Desk Lamp,2,1800
```

## Project Structure

```text
LAZERA/
├── server.js
├── package.json
├── lazera.db
├── sample.csv
├── README.md
└── public/
    ├── index.html
    ├── style.css
    └── app.js
```

## Installation

**1. Clone the repository**

```bash
git clone https://github.com/swarajsonalkar-web/LAZERA.git
cd LAZERA
```

**2. Install dependencies**

```bash
npm install
```

**3. Start the server**

```bash
npm start
```

Open: http://localhost:8014

## Future Improvements

- Advanced sales charts
- Date-range filtering
- Monthly and yearly comparisons
- Returns and refunds tracking
- Profit and loss analysis
- Excel file importing
- PDF report generation
- Authentication and multiple user accounts

## Developer

**Swaraj Sonalkar**

GitHub: https://github.com/swarajsonalkar-web

Email: swarajsonalkar99@gmail.com

---

*Turning raw sales data into meaningful business insights.*

Make a separate public in project directory and then paste the html,css and javascript file
