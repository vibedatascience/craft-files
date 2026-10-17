# craft-files

Files saved from the Craft apps on [rahulch.site](https://rahulch.site/) (PhotoCraft, VectorCraft, PdfCraft and the others).

Each file lives at `<app>/<id>/<name>`. The id is the first 12 hex characters of the file's SHA-256. Open a file in its app at `https://rahulch.site/<app>/?f=<id>/<name>`.

The apps write here through the GitHub contents API. How it works: `CRAFTFILES.md` in the site repo.
