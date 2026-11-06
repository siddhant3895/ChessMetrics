# ♟️ChessMetrics Pipeline-----------

A Python-based data engineering pipeline designed to parse, clean, and analyze personal PGN match history—specifically tracking performance against Chess.com computer personalities.

Whether you are analyzing your tactical blind spots or mapping out trends against specific bot personalities, this pipeline extracts raw game logs and turns them into clean, structured data.

---

## Features----

* **PGN Parsing Engine:** Efficiently processes raw `.pgn` files to extract key metadata (openings, move counts, elo ratings, and game outcomes).
* 
* **Bot Personality Tracking:** Tailored detection for Chess.com computer opponents to analyze which playstyles give you the most trouble.
* 
* **Data Cleanup:** Automatically strips out junk formatting, handling incomplete games or anomalies cleanly.
* 
* **Ready-to-Use Datasets:** Includes a sample data pipeline framework to test features out of the box.

---

## Repository Structure

This project follows clean data science directory standards:

```text
├── data/
│   └── raw/               # Drop your downloaded Chess.com PGN files here
├── src/                   # Core parsing and cleaning source scripts
├── LICENSE                # MIT License
├── README.md              # Project documentation
├── main.py                # Main execution entry point
├── requirements.txt       # Project dependencies
└── sample_games.pgn       # Pre-loaded match history for instant testing
