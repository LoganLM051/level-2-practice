# Week 5 Day 2 — Three requests, side by side

Fill this in from Postman or Bruno. **Never paste your API key in this file.**
This repo is public: anyone on the internet can read it.
Write `{{gemini_key}}` (the variable's name) instead.

| | Weather request | AI request | Add a dish |
| --- | --- | --- | --- |
| Method (GET / POST) | GET | POST | |
| Endpoint (the address, filled in for you) | `https://api.open-meteo.com/v1/forecast` | `https://generativelanguage.googleapis.com/v1beta/models/gemini-flash-lite-latest:generateContent` | `https://dummyjson.com/recipes/add` |
| Where the details go (query params or body?) | Query Params | Body (JSON) | |
| Headers I needed | None | x-goog-api-key: {{gemini_key}}  | |
| Does it need a key? | Yes | Yes | |
| Status I got | 200 OK | 200 OK | |
| The part of the response I care about (the path, like `current.temperature_2m`) | 'current.wind_speed_10m'| "text": "The Rolling Crust" | |

## What was different?

Write 2–3 sentences in your own words.
### I Noticed it was much faster to do the AI Request compared to the weather request, it required less work and most of the information is in different locations compared to the weather request. example : weather request information being in params, and AI request information being in body (JSON).

The AI request and Add a dish are both POST. What job does each one do?


## Did my dish really save?

What status did `Get my dish` give you? What does that tell you?


## Extra (if you finish early)

- Send the same prompt twice. Is the answer the same? Why might that be?
- Try a different model name in the address. What changed in the response?
