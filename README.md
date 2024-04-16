# Twitter-Scrapping-assignment-Node.js-
javascript const puppeteer = require('puppeteer');  (async () => {   const browser = await puppeteer.launch();   const page = await browser.newPage();   await page.goto('https://twitter.com/coindesk');    // Your code to scrape tweets goes here    await browser.close(); })(); ```
