# Chiplet Slicer

Drag a die on a 300 mm wafer, slice it into up to 16 chiplets, and see yield, die-to-die overhead and packaging cost trade against each other. Then inject a defect signature and read the wafer like a yield engineer.

- Live: https://vijay007-glitch.github.io/chiplet-slicer/
- Write-up: https://vijay007-glitch.github.io/posts/chiplet-slicer/

## Run it

It is one self-contained page, so open `index.html` in a browser. Or serve the folder:

```
python -m http.server 8000
```

The page loads web fonts from Google Fonts, so it needs a network connection for the intended typefaces.
