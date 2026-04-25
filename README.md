# Password Strength Checker

A real-time password strength analyser built with HTML, CSS, and JavaScript. Checks passwords against multiple security criteria and gives instant visual feedback.

## Features

- Real-time strength analysis as you type
- Entropy calculation (bits of randomness)
- Estimated crack time (offline brute-force attack)
- 6 security checks (length, uppercase, lowercase, numbers, symbols)
- Live improvement suggestions
- Show/hide password toggle
- Clean cybersecurity-themed UI

## How It Works

The checker evaluates passwords based on:

| Criteria | Points |
|---|---|
| 8+ characters | +15 |
| 12+ characters | +15 |
| 16+ characters | +10 |
| Lowercase letters | +10 |
| Uppercase letters | +10 |
| Numbers | +10 |
| Special characters | +15 |
| Multiple special chars | +5 |
| No repeating chars | +5 |
| Mixed character types | +5 |

**Entropy** is calculated as: `length × log₂(charset_size)`

**Crack time** estimates assume 10 billion guesses per second (offline attack scenario).

## Tech Stack

- HTML5
- CSS3 (CSS Variables, animations, grid layout)
- Vanilla JavaScript (no libraries or frameworks)

## Getting Started

```bash
git clone https://github.com/vithushickka/password-strength-checker.git
cd password-strength-checker
open index.html
```

Or just open `index.html` directly in any browser — no server needed.

## Screenshots

> Add a screenshot of the app here after running it!

## What I Learned

- DOM manipulation with JavaScript
- Real-time event handling with `input` events
- Security concepts: entropy, charset size, brute-force estimation
- CSS animations and transitions
- Responsive layout with CSS Grid

## Author

**Vithushickka Ramar**  
BSc (Hons) Computer Science — SLIIT City University  
[vithushickka@gmail.com](mailto:vithushickka@gmail.com)

## License

MIT License — free to use and modify.
