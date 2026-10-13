# ArrayBank — Banking Management System

A responsive, interactive educational website demonstrating how arrays can be used in a simplified banking management system. Built with plain HTML, CSS, and JavaScript.

## Features
- View sample customer accounts and combined balances
- Add a sample account
- Search accounts and filter by active/inactive status
- Deposit, withdraw, and transfer demo funds with validation
- View recent transactions
- Update account status or remove a sample account
- Educational explanations and code example showing how arrays support the application

## Where arrays are used
- `accounts` is an array of account objects. Each object holds a customer's name, account number, balance, and status.
- `transactions` is an array of transaction objects. New transactions are added to the beginning of the array and displayed in the recent-activity list.
- Array methods such as `filter()`, `find()`, `reduce()`, `push()`, and `unshift()` are used to search records, calculate balances, add accounts, and record activity.

## Run locally
Open `index.html` in a modern browser. No installation or build step is required.

## Deploy to GitHub Pages
1. Create a GitHub repository.
2. Upload `index.html` and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under build and deployment, choose **Deploy from a branch**, select `main` and `/(root)`, then save.

## Deploy to Vercel
Import the GitHub repository into Vercel. This is a static website, so no framework preset, build command, or output directory is needed.

## Important limitation
This is a classroom simulation, not real banking software. All data is stored in JavaScript arrays in the current browser session and resets when the page is refreshed. It has no authentication, database, encryption, or real payment/banking integration. Never enter real customer or financial information.
