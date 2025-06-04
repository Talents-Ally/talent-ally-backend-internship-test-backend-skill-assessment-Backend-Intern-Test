# Backend Intern Skill Assessment

Welcome to the Backend Intern Test! This short project is designed to assess your skills in setting up a project, working with APIs, frontend integration, and deploying a small web application.

---

## Task Overview

### Step 1: Install Node.js (5 mins)

1. Go to [https://nodejs.org](https://nodejs.org)
2. Download and install the **LTS version**
3. After installation, verify the setup using:

   ```bash
   node -v
   npm -v

**Step 2:** Download & Run the App Locally (15 mins)
Download the given studio-master.zip or clone the GitHub repo (if provided)

Unzip the folder

Open your terminal and navigate to the project folder

Run the following commands:

bash
Copy
Edit
npm install
npm run dev
Open your browser and go to: http://localhost:3000

**Submit:** Screenshot of the app running on your local system

**Step 3:** Add a Motivational Quote Feature (25 mins)
In src/ai/flows/, create a new file: generate-quote.ts

Inside it, return a motivational quote from a list (randomized or using ChatGPT API)

Example:

ts
Copy
Edit
export function generateQuote() {
  const quotes = [
    "Believe you can and you're halfway there.",
    "The best way to get started is to quit talking and begin doing.",
    "Success is not in what you have, but who you are."
  ];
  return quotes[Math.floor(Math.random() * quotes.length)];
}
In src/app/page.tsx:

Add an input field (optional) and a button

When clicked, call your quote function and display the result

**Submit:** Screenshot of your feature working in the browser

**Step 4: **Make the Homepage Mobile-Friendly (10 mins)
Use Tailwind CSS classes (sm:, w-full, text-center, etc.) to improve the layout

Use Chrome DevTools to test and ensure it looks good on mobile devices

**Submit: ** Screenshot showing your app in mobile view

**Step 5:** (Bonus) Deploy the App Online (Optional)
Push your code to GitHub

Go to https://vercel.com and sign in with GitHub

Import your repository and click Deploy

**Submit **(optional): Link to your live app

**Final Submission Checklist**
 GitHub repository link

 Screenshot of the app running locally

 Screenshot of the motivational quote feature

 Screenshot of mobile layout

 (Optional) Link to deployed app on Vercel

**Tip**: Keep your code clean, write meaningful commits, and ensure everything runs without errors.

Good luck!
