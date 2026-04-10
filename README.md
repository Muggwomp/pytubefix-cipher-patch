# pytubefix cipher.py patch
This repository contains a patched `cipher.py` for users of `pytubefix` who are hitting current YouTube player/cipher extraction failures.

## What this fixes
- signature function extraction failures
- nsig/throttling extraction failures
- certain empty Node response retry cases

## File included
- `cipher.py` — patched version

## How to use
Back up your existing `pytubefix/cipher.py`, then replace it with the file from this repository.

## Notes
- Modified from SzeMeng76's modified cipher.py patch.
- This patch was fully created and coded with ChatGPT-5.4 Codex
- I have set a simple automation that watches for new YouTube players. If a new player is discovered and fails cipher test, will patch as soon as am able.
- Working players as of 4-9-26:  
  "2430d1b0"  
  "57fefa84"  
  "592af824"  
  "5a9b5eed"  
  "6b334ac1"  
  "8a6e7bc4"  
  "8c57fc20"  
  "8c83ec2e"  
  "f4c47414"  
  "f4d92f0b"  
