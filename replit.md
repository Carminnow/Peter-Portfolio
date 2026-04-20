# Pete Portfolio

A static personal portfolio website for an artist named Pete, showcasing his artwork and background.

## Tech Stack

- **Frontend**: Plain HTML5 and CSS3
- **Server**: Python 3.11 built-in HTTP server (`python3 -m http.server`)
- **External**: normalize.css via CDN, Google Fonts

## Project Structure

```
Pete-Portfolio/
  index.html          # Main portfolio page
  style.css           # Custom styles
  images/             # Art images (pete-thinkful.png, abstract-red.png, spiral-zany.png, melted-rainbow.png)
  static-web-server.toml  # Static server config (port 5000)
README.md             # Project description
```

## Running

The app runs on port 5000 via:
```
cd Pete-Portfolio && python3 -m http.server 5000 --bind 0.0.0.0
```

## Deployment

Configured as a static site deployment with `publicDir: Pete-Portfolio`.
