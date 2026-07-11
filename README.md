# IMDb Open API

# ONLY FOR STUDY PURPOSE

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
MIT License

Copyright (c) 2026 Vikrant Choudhary 

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


![Project 1st Screenshot](https://res.cloudinary.com/esl7cqh0/image/upload/v1783786836/Screenshot_2026-07-11_215023_iasg52.png)
![project 2nd Screenshot](https://res.cloudinary.com/esl7cqh0/image/upload/v1783786993/Screenshot_2026-07-11_215302_uqeeny.png)
![Project 3rd Screenshot](https://res.cloudinary.com/esl7cqh0/image/upload/f_auto,q_auto/Screenshot_2026-07-11_211811_vwdcd3)
![Project 4th Screenshot](https://res.cloudinary.com/esl7cqh0/image/upload/v1783785719/Screenshot_2026-07-11_213143_vh3cku.png)
