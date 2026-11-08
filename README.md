# Megha Circuits website

Static multi-page site: open index.html. Regenerate every page with `python build.py`.

- Replace brand details, sample capabilities and certificates with the client's real information.
- Every picture slot on the site has its own image in assets/img (rendered by imggen.py, needs Pillow and numpy). To use the client's real photos, replace the matching file in assets/img; the file name is in the page's img tag.
- Login/sign-up is a browser-only demo (localStorage). Add a real backend before launch.
- Forms, quote estimates and the order tracker are demos.
