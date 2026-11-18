# Week 5 Day 2 — Three requests, side by side

Fill this in from Postman or Bruno. **Never paste your API key in this file.**
This repo is public: anyone on the internet can read it.
Write `{{gemini_key}}` (the variable's name) instead.

| | Weather request | AI request | Add a dish |
| --- | --- | --- | --- |
| Method (GET / POST) | | | |
| Endpoint (the address, filled in for you) | `https://api.open-meteo.com/v1/forecast` | `https://generativelanguage.googleapis.com/v1beta/models/gemini-flash-lite-latest:generateContent` | `https://dummyjson.com/recipes/add` |
| Where the details go (query params or body?) | Query Params | Body | |
| Headers I needed | None | x-goog-api-key | |
| Does it need a key? | None | {{gemini_key}} | |
| Status I got | 200 OK | 200 OK | |
| The part of the response I care about (the path, like `current.temperature_2m`) | data.current.wind_speed_10m = 5.4 (Units are km/h) | data.candidates[0].content.parts[0].text = "**The \"It’s Not My Fault\" Brisket Bomb Nachos**\n\nCrispy house-made tortilla chips piled high with 14-hour slow-smoked beef brisket, drizzled with spicy chipotle-bourbon BBQ sauce and warm white queso. Topped with pickled red onions, fresh jalapeños, crumbled cotija cheese, and a dollop of cilantro-lime crema. \n\n*(Because whatever went wrong with your day is officially... Nacho Problem.)*" | |

## What was different?

Write 2–3 sentences in your own words.
The AI request and Add a dish are both POST. What job does each one do?
Ask Gemini used a POST request, rather than GET with the weather. It also required the use of a Header to input the key, which was not a requirement from the weather API. Lastly, the query, or the equivalent of the query, was put in the Body, rather than the URL or Query Params.

## Did my dish really save?

What status did `Get my dish` give you? What does that tell you?


## Extra (if you finish early)

- Send the same prompt twice. Is the answer the same? Why might that be?
- Try a different model name in the address. What changed in the response?
