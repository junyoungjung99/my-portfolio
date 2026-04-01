# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Start of every session

Read these files before doing anything else:
- `progress.md` — what has been built and how
- `nextsteps.md` — outstanding tasks and content still to fill in

## Project overview

Single-page personal portfolio for an HCI Master's student (potentially PhD-bound), targeted at the HCI research community with a focus on Human-AI Interaction. Built with plain HTML and CSS — no frameworks, no build tools, no dependencies.

## Development

No build step. Open `index.html` directly in a browser. No package manager, no server required.

## Stack

- Single `index.html`, single `style.css`
- No JavaScript unless explicitly requested
- No frameworks (no Tailwind, Bootstrap, React, etc.)
- No preprocessors (no Sass, PostCSS, etc.)

## Aesthetic

Minimal, dark. Dark backgrounds, light text, low-contrast accents. Typography and whitespace over decoration. Do not introduce light-mode assumptions.

## Audience

HCI researchers and faculty — people who read CHI and CSCW papers, evaluate portfolios for PhD admissions or collaborations. Content framing should match an academic context, not a commercial UX/product context.

## Rules

- **Ask before restructuring.** Do not reorganize sections, rename files, or change layout hierarchy without explicit approval.
- **Only build what is asked for.** No speculative additions, no extra sections or components.
- **No new files** unless clearly necessary and discussed first.
- **No frameworks.** Find the plain HTML/CSS solution first.
