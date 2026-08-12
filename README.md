# The Clean Data Sanctuary

A simple browser-based tool that demonstrates data cleaning using JavaScript's `.filter()` method on a simulated dirty e-commerce inventory array.

## What It Does

Takes a raw array containing mixed types — empty strings, numbers, `undefined`, whitespace, and placeholder values — and filters it down to only valid product name strings.

## How to Use

1. Open `data-cleaner.html` in any browser
2. Click **Run Data Purge & Render**
3. The left panel shows the raw dirty array; the right panel shows the sanitized inventory

## Cleaning Rules

An item is kept only if it:
- Is of type `string`
- Is not empty or whitespace-only
- Is not `"UNKNOWN_PRODUCT"`

## Tech

Plain HTML, CSS, and vanilla JavaScript — no dependencies.
