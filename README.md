# Bankist 🏦

A fake banking app I built while working through **Jonas Schmedtmann's "The Complete JavaScript Course"** on Udemy.

Log in with a demo account and you can view your movements, transfer money, request a loan, close your account, and sort your transactions. You get logged out automatically after 2 minutes of inactivity.

## Demo accounts

| User | PIN  | Owner            |
| ---- | ---- | ---------------- |
| `js` | 1111 | Jonas Schmedtmann |
| `jd` | 2222 | Jessica Davis     |

The username is just the owner's initials, lowercased.

## Features

- **Login** with username + PIN
- **Movements** list with dates ("Today", "3 days ago", or a real date) and currency formatting per account
- **Balance** and a summary of money in, out, and earned interest
- **Transfer** money to another account (with balance checks)
- **Request a loan** (approved only if you have a deposit of at least 10% of the amount)
- **Close account** with user + PIN confirmation
- **Sort** movements ascending / descending
- **Auto logout** after inactivity, reset on any action

## What I learned

- Organising app state in account objects and a `accounts` array
- Array methods in a real app: `map`, `filter`, `reduce`, `find`, `findIndex`, `some`
- Building DOM rows from data with template strings and `insertAdjacentHTML`
- Using `Intl.NumberFormat` and `Intl.DateTimeFormat` for locale-aware money and dates
- Timers with `setInterval` / `clearInterval` and `setTimeout`
- Handling forms and stopping the default submit with `e.preventDefault()`

## Files

- `index.html` — the layout
- `style.css` — the styling
- `script.js` — all the app logic
- `logo.png`, `icon.png` — assets

## Running it

No setup needed. Just open `index.html` in your browser, log in with one of the demo accounts, and explore.

## Credit

Project idea and starter HTML/CSS come from the course:
[The Complete JavaScript Course: From Zero to Expert! — Jonas Schmedtmann](https://www.udemy.com/course/the-complete-javascript-course/)
