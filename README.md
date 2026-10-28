# ITE183 Lab 2 - WebSocket Server (Cat Cafe Edition)

A real-time multi-client chat built with the Bonezegei Scripting Language v1.3.3.
The server serves static files, returns a custom 404 page, and broadcasts WebSocket
messages to every connected client. The frontend is a cat-themed chat room with two rooms.

## Requirements
- Bonezegei v1.3.3 (`bonezegei -v`)

## Run
```bash
bzg install
bzg run
```
Open `http://localhost:8000` in two or more browser windows and chat.
Visit any other path (e.g. `/abc`) to see the custom 404 page.

## Project structure
```
app.bzg          HTTP + WebSocket server
package.json     Project / dependency specification
public/
  index.html     Cat Cafe chat client
  404.html       Custom 404 page
```

## Documentation
**Figure 1:** `bonezegei -v` showing version 1.3.3
**Figure 2:** `bzg install` and `bzg run` server startup
**Figure 3:** Multi-client real-time chat across browser windows
**Figure 4:** Custom 404 page

(Put your screenshots in a `documentation/` folder and link them here.)

## License
MIT
