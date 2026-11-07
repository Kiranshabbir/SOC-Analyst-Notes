# Day 12 - HTTP and the Browser Network Tab
Date: Nov 7, 2026

## 1. What I learned
- HTTP is the set of rules a browser uses to talk to a web server. HTTPS is the secure version.
- A browser sends a request, and the server sends back a response.
- GET asks for data (like a web page). POST sends data to the server (like a login form).
- A status code tells me what happened: 200 = OK, 301 = moved (redirect), 404 = not found, 500 = server error.

## 2. What I did
- I reviewed my HTTP in Detail notes and read the tutorial: Inspect network activity (Microsoft Edge DevTools).
- I opened Chrome DevTools (F12), clicked the Network tab, and reloaded youtube.com. https://www.gstatic.com, method GET, status code 200 (OK).
- I also saw status code 404, which means not found.
- I finished the TryHackMe room: Windows Fundamentals 1.


## 3. New words
- HTTP = Hypertext Transfer Protocol
- HTTPS = HTTP Secure
- Request: what my browser asks for.
- Response: what the server sends back.
- GET: ask for data.
- POST: send data.
- Status code: a number that shows the result of a request.

## 4. What was hard
- Nothing was hard.

## 5. Explain in 2 sentences
- When I open a website, my browser sends a request to the server, and the server sends back a response. The response has a status code, like 200, which means OK.
