# 字里行间 · Между строк

A small, invitation-based Russian reading evaluation.

This public repository contains the web page only. Scoring records and method mappings are not stored in this repository.

The page at `/` saves the reviewer's answers to the study owner's backend after each item; without a valid invitation link it sends nothing and answers stay in the browser. `/review-2026-10/` forwards to `/`, keeping the invitation. The 2026-09 demonstration page that used to be at `/` remains in this repository's history. The embedded Supabase key is a publishable key; data access is restricted by the backend.

Font licenses are embedded in the HTML.
