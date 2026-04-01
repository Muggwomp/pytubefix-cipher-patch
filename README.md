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
This is an unofficial community patch and has not yet been submitted upstream. Modified from SzeMeng76's modified cipher.py patch.
This patch was fully created and coded with ChatGPT-5.4 Codex
I can't guarantee how long this patch will work as YouTube seems to be updating their players about 1 - 2 weeks at this point.
