# EchoMind
EchoMind is a personal pipeline that converts iOS Voice Memo recordings — spoken reflections captured in the moment — into clean, readable Markdown notes stored in this Obsidian vault.

The goal is to make past reflections easy to revisit. Voice memos are ephemeral and hard to search. Transcribed, formatted notes become a permanent, browseable record of your thinking over time.

## The Problem

- Voice memos pile up and never get reviewed.
- Raw transcripts are hard to read — full of fillers, false starts, and run-on sentences.
- There's no structure: no titles, no key points, no way to scan quickly.

## The Solution

A lightweight local script that takes `.m4a` files and produces polished Markdown notes in this vault — formatted in the style of Typeless: clean prose, structured key points, and a one-line summary at the top.

## Workflow

1. Record a voice memo on iPhone as usual.
2. Export the `.m4a` file to your Mac (AirDrop, iCloud Drive, or USB).
3. Run the EchoMind script pointing at the file(s).
4. The note appears in `Reflections/YYYY/MM/` in this vault, ready to read in Obsidian.

## What a Finished Note Looks Like

Each note has:
- A **meaningful title** (not "Voice Memo 47")
- A **one-sentence summary** of the core idea
- **Key thoughts** as bullet points — the distilled takeaways
- **Full reflection** as clean prose — your words, just edited for readability

## Scope

- This is a personal tool for one user.
- No database, no web app, no sync service — just a script and a Markdown vault.
- Notes are immutable once created unless manually edited.
