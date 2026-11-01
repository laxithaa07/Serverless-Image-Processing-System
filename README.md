# Serverless Image Processing — PixelCloud

Upload an image, apply effects and download the processed result using the browser Canvas API.

## Features
- Image upload and validation
- Grayscale, sepia, brightness and blur
- Original and processed preview
- Download PNG

## Technology
HTML5, CSS3 and Vanilla JavaScript. No frameworks or package installation required.

## Run locally
Open `index.html` in a modern browser. Alternatively, run `python -m http.server 8000` in this folder and visit `http://localhost:8000`.

## Project note
This demo processes images locally in the browser. It does not deploy a cloud function or upload files to cloud storage.

## GitHub upload
1. Extract this ZIP.
2. Create a new GitHub repository.
3. Upload the extracted files.
4. To publish, open repository Settings → Pages and select the `main` branch and root folder.

This is a working front-end academic prototype, not a complete production cloud backend. For production, add secure APIs, authentication, database/object storage, access controls, monitoring and backups.
