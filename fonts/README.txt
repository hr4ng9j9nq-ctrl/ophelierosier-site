Monument Extended — bundled.
============================

Files in this folder are loaded by the @font-face block in
client/src/index.css (family name "Monument Extended"):

    MonumentExtended-Regular.woff  (compressed, loaded first)
    MonumentExtended-Regular.ttf   (fallback)

The bundled file is "PP Monument Extended Black" (weight 900), which is
the single weight the design uses. The @font-face maps all weights
(100–900) to this file.

Optional: for the smallest possible download, convert the .ttf to .woff2
(needs the Brotli extension, e.g. `pip install brotli fonttools` then
`fonttools ttLib.woff2 compress MonumentExtended-Regular.ttf`) and add a
woff2 url to the @font-face src, before the woff line.
