# Guitar Key & Chord Trainer

A mobile-friendly browser trainer for learning how major keys, diatonic chords, Roman numerals, and common chord progressions fit together.

## Current Version

Version 0.2

## What It Does

The app has two main sections:

### Learn

The Learn section is designed to be studied before using the quizzes.

It includes:

- The universal major-key chord pattern:
  - Major – minor – minor – Major – Major – minor – diminished
  - I – ii – iii – IV – V – vi – vii°
- A Key Explorer for all 12 major keys
- A focus on common guitar keys: C, G, D, A, E, and F
- The seven diatonic chords in each selected key
- Chord quality for each scale degree
- Several common chord progressions shown both as Roman numerals and actual chord names

### Practice

The Practice section currently includes three quiz modes:

1. **Key → Chord**
   - Example: Which chord is IV in G major?

2. **Chord Progression → Key**
   - Example: G – D – Em – C. What is the most likely major key?

3. **Chord → Roman Numeral**
   - Example: In G major, what number is Em?

The trainer tracks:

- Correct answers
- Current streak
- Accuracy

Stats are stored locally in the browser using `localStorage`.

## Files

The project currently requires only one application file:

- `index.html`

This file contains all HTML, CSS, and JavaScript.

## Running Locally

Open `index.html` in any modern web browser.

No server, build process, package manager, or external dependency is required.

## GitHub Pages

This project is designed to run directly from GitHub Pages.

Recommended configuration:

- Source: **Deploy from a branch**
- Branch: **main**
- Folder: **/ (root)**

Once GitHub Pages is enabled, the app can be opened directly from its public Pages URL.

## Mobile Use

The interface is designed primarily for phone use, especially iPhone Safari.

The GitHub Pages site can also be added to the iPhone Home Screen for app-like access.

## Design Goals

- Beginner-friendly
- Guitar-oriented
- Teach before testing
- Connect chord names with Roman numerals
- Emphasize practical musical understanding rather than memorization alone
- Keep the entire application simple enough to maintain as one self-contained `index.html` file

## Learning Priorities

The initial learning path emphasizes these major keys:

1. C
2. G
3. D
4. A
5. E
6. F

Future versions may add:

- Minor keys
- Relative major/minor relationships
- Scale notes
- Seventh chords
- More progression types
- Ear-training concepts
- Progress tracking by key
- More guided learning modes
- Guitar-specific chord voicings
- Suggestions for scales to play over a progression

## Updating the App

When a new version is generated:

1. Replace the existing `index.html` in the GitHub repository.
2. Commit the change to `main`.
3. GitHub Pages will automatically redeploy the updated version.

## Project Philosophy

The goal is not simply to quiz chord theory. The app should help a guitarist understand why chords belong together, recognize the musical function of those chords, and gradually connect that knowledge to real playing and songwriting.
