# Simple Calculator

Basic calculator in plain HTML/CSS/JS with an `eval()`-backed expression engine.
Buttons append characters to the display input; `=` evaluates whatever is in it.

## Operations

`+ - * / % .` plus `C` (clear) and `=` (evaluate). Input comes only from the
buttons - the display is a `readonly`-style text input.

## Run

```bash
git clone https://github.com/ErfanBagheri404/Simple-Calculator.git
cd Simple-Calculator
```

Open `index.html`.

## Files

| file | role |
|---|---|
| `index.html` | keypad + display |
| `index.js` | `appendToDisplay`, `clearDisplay`, `calculate` |
| `style.css` | keypad grid and button states |
