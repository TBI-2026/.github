# CTRL + F - TBI 2026 Project

Scalable retrieval system project for **Temu Balik Informasi (TBI)**.

## Team Members

- Ramy Ardya Ramadhan (2306210393)
- Nadia Rahmadina Aristawati (2306207972)
- Muhammad Zaid Ats Tsabit (2306224410)
- Belva Ghani Abhinaya (2306203526)
- Syauqi Muhammad Yasman (2306275752)

## Project Scope

We are building a scalable multi-service book retrieval platform with:

- Keyword-based retrieval
- Hybrid retrieval (BM25 + vector kNN)
- Microservice architecture and async messaging

## Repositories

- [frontend](https://github.com/TBI-2026/frontend)
- [backend](https://github.com/TBI-2026/backend)
- [authentication](https://github.com/TBI-2026/authentication)
- [location](https://github.com/TBI-2026/location)
- [search-service](https://github.com/TBI-2026/search-service)

## Progress Status (15 May 2026)

- Core services and API are running
- Live search integration is available in frontend
- Retrieval baseline (keyword search) is implemented
- OpenSearch-based `search-service` is implemented with:
- `GET /search` for hybrid retrieval (BM25 + vector kNN + RRF)
- `POST /index` and `POST /index/bulk` for indexing
- RabbitMQ consumer for async indexing on `book.created`

## Deliverables

- Progress Report: submitted with team members and GitHub links
- Final (24 May 2026): GitHub, hosted demo link, and YouTube demo link
