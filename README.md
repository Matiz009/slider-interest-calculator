# Slider Interest Calculator

An interest calculator in JavaScript. Sliders set the principal, years and rate, and the interest updates as you move them.

## Screenshot

_Screenshot coming soon._

## Features

- Sliders for principal ($1 to $10,000), years (1 to 10) and rate (1 to 100%)
- Simple interest and total to pay update live

> **Known issue (TODO):** `pSlider.value + simpleInterest` joins two strings instead of adding them, so the total to pay comes out wrong (for example `$50025` instead of `$525`).

## Tech stack

Vanilla JavaScript, HTML (served from `index.php`)

## Getting started

```bash
git clone https://github.com/Matiz009/slider-interest-calculator.git
cd slider-interest-calculator
php -S localhost:8000
# open http://localhost:8000
```

## Project structure

```
index.php  Page with the sliders
app.js     Calculation logic
```

## Author

**Mati ul Rehman** - [github.com/Matiz009](https://github.com/Matiz009)
