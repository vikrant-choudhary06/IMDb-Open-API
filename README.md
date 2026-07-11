# IMDb Open API

Unofficial REST API for searching IMDb data, built with FastAPI and deployed on Render.

**Live docs:** https://cut-crew-all.onrender.com/docs

## ⚠️ Disclaimer
This is an unofficial project, not affiliated with or endorsed by IMDb.
Intended for educational/personal use — check IMDb's Terms of Service
before using this in production.

## Base URL
https://cut-crew-all.onrender.com

## Endpoints

### GET /search/{query}
Search IMDb by title/name string.

**Example:**
GET /search/inception

**Response:** (fill in actual shape from a real response)
```json
{
  "results": [...]
}
```

## Tech Stack
- Python / FastAPI
- Deployed on Render

## Running locally
```bash
git clone https://github.com/vikrant-choudhary06/CutCrew/tree/main
cd backend
npm i
npm run dev 
```

## Note on cold starts
Hosted on Render's free tier — the first request after inactivity may take
30–60s while the instance spins up.

## License


![Project 1st Screenshot](https://res.cloudinary.com/esl7cqh0/image/upload/v1783786836/Screenshot_2026-07-11_215023_iasg52.png)
![project 2nd Screenshot](https://res.cloudinary.com/esl7cqh0/image/upload/v1783786993/Screenshot_2026-07-11_215302_uqeeny.png)
![Project 3rd Screenshot](https://res.cloudinary.com/esl7cqh0/image/upload/f_auto,q_auto/Screenshot_2026-07-11_211811_vwdcd3)
![Project 4th Screenshot](https://res.cloudinary.com/esl7cqh0/image/upload/v1783785719/Screenshot_2026-07-11_213143_vh3cku.png)
