# Tip Calculator

A simple, single-page tip calculator. Enter a bill amount, choose a tip percent, optionally split the total between people, and see the tip, grand total, and per-person share update as you type.

Open `index.html` in a browser. There is no build step and no dependencies.

## Features

- Bill amount input
- Tip presets: 10%, 15%, 18%, 20%, and 25%
- Custom tip percent
- Split by number of people
- Live results for tip, total, and amount per person
- Basic validation for negative amounts, invalid numbers, and a people count below 1

## How to use

1. Clone the repo:

   ```bash
   git clone https://github.com/sushanshetty2601-pixel/tip-calculator.git
   ```

2. Open `index.html` in your browser.

3. Enter the bill, pick a tip (or Custom), and set how many people are splitting.

## How the math works

```
tip    = bill × (tip percent / 100)
total  = bill + tip
each   = total / number of people
```

Example: a $100 bill at 20% split 4 ways is $20 tip, $120 total, and $30 per person.

## Files

- `index.html` — markup, styles, and JavaScript in one file
