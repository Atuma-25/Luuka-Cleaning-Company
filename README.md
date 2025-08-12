Cleaning Service — Ready-to-Use Static Website
===============================================

What's included:
- index.html (Home)
- services.html (Services)
- booking.html (Booking page with Calendly embed)
- about.html (About)
- contact.html (Contact + Formspree contact form)
- assets/styles.css
- assets/script.js
- README.md (this file)

Quick setup steps (launch in under 1 hour)
-----------------------------------------
1. Edit placeholders:
   - Replace 'YOUR COMPANY NAME', phone, email, and 'YOUR CITY' in the HTML files.
   - In booking.html, replace 'https://calendly.com/YOUR_CALENDLY_USERNAME/30min' with your Calendly scheduling link.
   - In contact.html, replace the Formspree action URL with your Formspree form endpoint (or replace with another form handler).

2. Enable booking payments (optional):
   - Calendly supports payments via Stripe and PayPal on paid plans. Sign in to Calendly, go to Event Types -> Payments and connect Stripe/PayPal.
   - Alternatively, include a payment link in the Calendly confirmation message (Stripe Checkout link or PayPal.Me).

3. Hosting:
   - Upload all files to any static host (Netlify, Vercel, GitHub Pages, or your web host).
   - If using a cPanel host, zip the files and upload via File Manager, then extract into public_html (or the site root).

4. Domain:
   - Point your domain (e.g., example.com) to your host; follow your host's DNS instructions.

5. Contact form:
   - This template uses Formspree for contact handling. Sign up at https://formspree.io/, create a form, and replace the action URL.
   - If you prefer email notifications without third-party services, you'll need a backend; I can help with that.

6. Customization:
   - To accept deposits/payments during booking without Calendly payments, we can integrate Stripe Checkout + a tiny serverless function — ask me and I will produce the exact code.

Need additional help?
---------------------
If you'd like, I can:
- Convert this into a WordPress theme/Elementor-ready package.
- Add Stripe Checkout integration (serverless) so customers pay at booking.
- Customize copy, pricing, and images for your brand.

Enjoy! — I've packaged the site below for download and upload to your host.
