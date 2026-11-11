Snake Puzzle (Bravestars v2.2.45) - Unity WebGL build, saved from an Apps Script page.

index.html                              - decoded page (shell)
scripts/inline_script_1_obfuscated.js   - the page's inline script (jsjiami v7 obfuscated)
scripts/st39_pg_stand.js                - st39/pg stand.js: Playgama bridge (ads, storage, etc.)
scripts/EleaseMullin_pbu.js             - EleaseMullin/route pbu.js: Unity loader glue

NOT included - the Unity build itself (all images and sounds are packed inside it), loaded from:
  https://cdn.jsdelivr.net/gh/EleaseMullin/route@32f851663be992cb94f60db5d9def6a693ea27ae/data/loader.js
  .../data/disp.js   (Unity data file: textures, audio, etc.)
  .../data/file.js   (Unity framework)
  .../data/show.js   (WebAssembly code)
Also: https://cdn.jsdelivr.net/gh/KrMattsson/base@ff3745bf2ef2ac380041582b07f700c83401e353/src/pg/pg-bridge.js
