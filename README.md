# Trendyol HTTP Request Analysis

Turkce README: [Turkce Ozet](turkce/README.md)

In this project, Chrome DevTools was used to analyze HTTP requests made on the Trendyol website. Within the context of client-server architecture, GET and POST requests, status codes, header information, CORS policies, and network traffic were examined.

## What Was Analyzed

| Task | Method | Status | Focus Area |
| --- | --- | --- | --- |
| 1 | GET | 200 OK | Homepage load request |
| 2 | POST | 400 Bad Request | Login attempt request |
| 3 | GET | 200 OK | Product-page request behavior |
| 4 | GET | 301 Moved Permanently | Favorites route redirect |
| 5 | PUT | 200 OK | Cart quantity update |
| 6 | DELETE | 204 No Content | Cart item removal |
| 7 | POST | 400 Bad Request | Guest-user flow validation |

## Task Pages

- Open all tasks from one page: [English Task List](https://gulsahunal.github.io/trendyol-http-request-analysis/evidence/en/index.html)

## Repository Structure

- docs/: Request reference and analysis notes
- evidence/: English and Turkish task pages with screenshots
- evidence/raw/: Original exported source files
- turkce/: Turkish summary documentation
