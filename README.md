# Bulk Lottie Viewer

Bulk Lottie Viewer is a local review tool for inspecting many Lottie JSON files at once.

## What it does

- Drag and drop multiple JSON files
- Drop folders and scan nested files
- Search the loaded list by filename
- Preview one animation in a larger stage
- Pause, resume, scrub, and change playback speed
- Show file size, dimensions, frame count, and duration

## Why it exists

This was built for batch checks. The goal is to make it easy to load a pile of exports, spot the wrong file fast, and inspect the selected animation without losing the list.

## About

- Runs locally in the browser
- Accepts `.json` Lottie files
- Skips invalid files and keeps the rest of the batch
- Uses `lottie-web` for playback

## Run it

```bash
npm install
npm run dev
```

Open `http://localhost:5173`.

## Build

```bash
npm run build
```
