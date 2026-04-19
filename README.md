# Trendyol HTTP Request Analysis

[Türkçe](turkce/README.md)

This project documents a practical HTTP request analysis workflow executed with Chrome DevTools on Trendyol.
Requests and responses were examined to understand client-server communication, status codes, headers, CORS behavior, and network timing.
The same 7 tasks are documented directly in both language versions.

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

## Analysis Scope

- Request method and endpoint behavior
- HTTP status code validation
- Request and response header observations
- CORS and preflight behavior where applicable
- Network timing and waterfall details

## Result Summary

- 7/7 tasks completed successfully in the documented run.
- Expected status responses were observed for each selected request flow.
- Request/response details and screenshots were captured for reproducibility.
- This repository is published as a project presentation.

## Task Pages

- Open all tasks: [Task List](https://gulsahunal.github.io/trendyol-http-request-analysis/evidence/en/index.html)

## Repository Structure

- docs/: English technical notes and request references
- evidence/: Turkish and English task pages for project presentation
- evidence/raw/: Original exported source files
- turkce/: Turkish summary documentation
