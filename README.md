# Chocoholics

Website and online ordering system for **Chocoholics**, a late-night dessert shop on Mansfield Road in Nottingham. 

Live site: [chocoholics.xyz](https://chocoholics.xyz)

## Why I built this
Most local dessert shops rely entirely on delivery apps like Uber Eats and Deliveroo, which take huge commissions and mark up menu prices. I wanted to build a fast, mobile-friendly website where customers can browse the full menu, check if they are in the local delivery zone, and order directly from the shop without extra app fees.

## What it does
* **Direct Ordering & Payments:** Customers can build a basket for collection or delivery and pay by card using **Stripe Checkout**.
* **Customer Accounts & Rewards:** Built with **Supabase**. Creating an account gives customers 5% off direct orders and automatically adds 10% credit to their wallet on every 10th completed order.
* **Dessert Match Quiz:** A quick interactive tool that filters the menu based on flavour and treat type if someone isn't sure what to order.
* **Postcode Radius Check:** Checks whether a customer's Nottingham postcode falls within the shop's 4-mile delivery radius before checkout.
* **Sweet Invite Generator:** Lets users write a custom note and share a formatted dessert invite link straight to WhatsApp.

## Tech used
* **Frontend:** HTML, CSS, Vanilla JavaScript
* **Database & Auth:** Supabase
* **Payments:** Stripe
* **Hosting:** GitHub Pages (custom domain via `CNAME`)
* **Development Tools:** Used ChatGPT as a coding assistant to help debug issues, structure JavaScript logic, and speed up development.

## What I learned
Building this taught me how to connect a static frontend to real backend services. Working alongside ChatGPT helped me understand how APIs, authentication states, and payment webhooks fit together, while I focused on designing the user experience, testing the features, and getting the live site deployed.
