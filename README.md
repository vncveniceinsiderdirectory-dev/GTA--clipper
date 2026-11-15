# GTA--clipper

GTA 6 clip harvester for the Venice News Channel.

## What it does
Takes a gameplay recording or stream capture you have the rights to use, cuts a short vertical clip (default 30 seconds, 1080x1920) ready to post as a YouTube Short on the Venice News Channel. Clips drive traffic to the Venice Insider Directory, the Abbot Kinney Merchants Report, the Daily Income Apps, and Venetian Threads.

## Usage
1. Put a source video in the `input/` folder (or pass a path).
2. Run: `python3 clipper.py --input input/source.mp4 --start 00:01:15 --duration 30 --title "GTA 6 — first chase"`
3. The finished Short lands in `output/` as a vertical 1080x1920 mp4 with the title burned in as a caption header.

## Rules
- Only clip footage you own or have permission to use.
- Original Venice commentary/captions on every clip — no straight re-uploads.
- Every clip description links back to the Venice Insider Directory subscribe page and the Daily Income Apps board.

## Status
Scaffold live Nov 14, 2026. GTA 6 launches Nov 19, 2026 — clip channel must be ready before launch week.
