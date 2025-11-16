# Vibe-Code-Until-It-Dies

Welcome to the digital equivalent of a house of cards built during a mild earthquake. This repository is a testament to "vibe-driven development"—a process where code is written based on pure instinct, a disregard for best practices, and an unhealthy amount of caffeine.

**Disclaimer:** Every line of code here has a 50-50 chance of working. It either works, or it doesn't. If you encounter a bug, that's not a bug; it's a feature. If the whole thing crashes your browser, consider it a feature with attitude.

## The "Projects"

This collection contains a couple of web-based games that were coded with more hope than skill.

### 1. Minesweeper

-   **File:** `minesweeper/index.html`
-   **The Vibe:** A sleek, modern, dark-mode take on Minesweeper for people who enjoy anxiety.
-   **The Twist:** Forget what you know about Minesweeper. Your first click is safe. ONE other random tile is also safe. Every single other tile is a bomb. The goal is to find the two safe spots in a field of certain doom.
-   **The Bullshit:** The bomb placement logic is... creative. The win condition is checked with the fervor of a squirrel looking for a nut it buried last winter. It *probably* works. The timer is there to remind you how much of your life you're wasting.

### 2. BluCoin Clicker

-   **File:** `BluCoin Clicker/index.html`
-   **The Vibe:** A classic incremental/clicker game where you can become a fake crypto-millionaire. It has a cool blue theme and an animated title that triggers after 1000 clicks to reward your descent into madness.
-   **The Twist:** It's about "BluCoin," which is definitely not a real cryptocurrency. Don't try to cash out.
-   **The Bullshit:** The save/load system uses `localStorage` and a prayer. If your score vanishes, consider it a market crash. The background music is supposed to start after your first click, but it might have other plans. The mute button is your only real friend here. The game's balance is non-existent; have fun.

### 3. Fidget Page

-   **File:** `fidget-page/index.html`
-   **The Vibe:** A digital playground for people with the attention span of a goldfish. A smorgasbord of pointless but satisfying interactions, complete with a dark-mode aesthetic and surprisingly detailed sound effects.
-   **The Twist:** It's a collection of UI elements divorced from any purpose, existing only to be clicked, toggled, and spun. It's a monument to over-engineering the trivial.
-   **The Bullshit:** This single HTML file loads Tailwind CSS and Tone.js from a CDN to create a surprisingly complex suite of toys. There's a rotary knob with adjustable snapping, a bubble wrap simulator, and a "DO NOT PRESS" button with canned responses. The JavaScript has more synths defined than a 1980s pop band.

### 4. Phone Number Input

-   **File:** `phone number/index.html`
-   **The Vibe:** A masterclass in user-hostile design, masquerading as a simple contact form.
-   **The Twist:** Why would you let a user *type* their phone number when you can make them *discover* it? This form features a range slider for the number input, forcing you to painstakingly drag your way to the correct 10-digit sequence from a pool of 9 billion possibilities.
-   **The Bullshit:** The country code dropdown is a beautiful decoy, lulling you into a false sense of security before you're confronted with the slider. The entire functionality hinges on a single line of inline JavaScript: `oninput="phone.value = slider.value"`. It's both minimalist and a crime against usability.

### 5. Typing Racer Pro

-   **File:** `Typing Racer/index.html`
-   **The Vibe:** A surprisingly functional typing game where you race against bots with questionable ethics.
-   **The Twist:** Buy upgrades, freeze your opponents, and grind for cash. It's a feature-rich descent into madness, all to prove you can type slightly faster than a script.
-   **The Bullshit:** The bots have a chance to freeze *you*. You can buy "Hand Warmers" to block their attacks, which is a feature that was definitely planned from the start and not added in a panic. The game's economy is balanced on a knife's edge, and the save system will probably remember your cash. Probably.

## How to Run This Masterpiece

1.  Clone this repository (if you hate trees).
2.  Navigate to a project directory of your choosing.
3.  Open the `index.html` file in your favorite web browser.
4.  If it doesn't work, try refreshing. If it still doesn't work, well, we told you so.

## Contributing

Feel free to submit a pull request, but be warned: you are entering a fragile ecosystem. Touching anything might bring the whole fragile structure tumbling down.

**Golden Rule:** If it works, don't touch it. If it doesn't work, it's probably not worth fixing.

Good luck. You'll need it.

---

This Readme was made using AI as well minus this section. My goal is to prove how dumb "vibe coding" really is by creating the most pointless projects until the LLM is unable to do anything without encountering an error.
