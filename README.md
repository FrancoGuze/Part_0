# Part_0
Full Stack Open Exercises


Browser->Server: HTML POST https://studies.cs.helsinki.fi/exampleapp/new_note
Server->Browser: HTTP 302 -> HTTP GET /notes 
Browser->Server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/main.css
Server->Browser: main.css
Browser->Server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/main.js
Server->Browser: main.js
Browser->Server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/data.json
Server->Browser: data.json
note over Browser: The data is send as the body of the POST request. The server can access to this data by using the req.body. Then the server creates a new note object and adds it to the notes matrix 
