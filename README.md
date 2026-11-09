# JavaScript course exercises

This is a study fork of Jonathan MirCha’s [JavaScript course repository](https://github.com/jonmircha/youtube-js). Jonathan MirCha authored the lessons and teaching materials. The [original Spanish README](README.es.md) includes the video playlist and the author’s notes on the exercises.

## Run a lesson locally

From the repository root, start a static HTTP server with Python 3:

```sh
python -m http.server 8000 --bind 127.0.0.1
```

Open [the modules lesson](http://127.0.0.1:8000/01_modulos.html) and open the browser console to see its output. The page loads [modulos.js](js/modulos.js) as an ES module. Serving the directory over HTTP lets the browser resolve its module imports.

## Other exercises

The numbered HTML pages cover fundamentals, asynchronous code, the DOM and HTTP requests. Each page is a separate entry point. Some later exercises call external services or require a separate backend. The repository has no automated test command; check each exercise against the corresponding course lesson.
