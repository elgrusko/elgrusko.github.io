# camera-teardown

Hardware reverse-engineering writeup of a ~€20 white-label cloud IP camera.
Part 1: recon, teardown, firmware. Static site, no build step, no dependencies.

## Structure

```
.
├── index.html      the writeup (single page)
├── style.css       phrack-style stylesheet (mono, black/white/red)
├── static/         put your images here (01-bench.jpg, 02-uart.jpg, 03-spi-dump.jpg)
└── README.md
```

## Use

Open `index.html` in a browser, or serve the folder:

```
python3 -m http.server
```

then visit http://localhost:8000

## Notes

- Edit the `[your handle]` line in `index.html` (masthead).
- Follows a light/dark palette automatically (system preference).
- Before publishing, blur the manufacturer label in `01-bench.jpg` to keep the vendor anonymous.
# elgrusko.github.io
