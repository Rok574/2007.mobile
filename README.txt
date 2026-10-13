Pocket 2007 - local copy
========================
Run (needs a web server; double-clicking index.html will not work):
  cd into this folder, then:  python3 -m http.server 8000
  open http://localhost:8000 in Safari/Chrome.
On iPhone: a-Shell has python3; cd to this folder and run the same command.

Notes
- manifest.json points at local copies in fw/ (hashes verified against the original).
- jit/ (optional accelerator) and service-worker.js (Keep offline) are not included; the phone runs without them.
- dist/ holds emu.js and emu.wasm.

Credits
Original site, emulator and concept: 2007.mobile. iPhone OS 1.0 is Apple's software.
index.html is an unofficial alternate front end. For personal use; get the owner's permission before publishing or redistributing.
