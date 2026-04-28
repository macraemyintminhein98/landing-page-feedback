# Landing Page Feedback Service

**Apex Feedback** offers concise, actionable conversion-focused feedback for your landing page. 

**Service includes:**
*   Personalized 3-5 minute Loom video review.
*   Bullet-point summary of key recommendations.
*   Focus on headlines, CTAs, clarity, trust signals, and overall conversion.

**Price:** $9.99 per review.

**How to Use:**
1.  **Deploy this simple landing page.**
2.  **Replace `YOUR_STRIPE_PUBLISHABLE_KEY` and `PRICE_ID_FOR_9_99`** in `index.html` with your actual Stripe keys.
3.  **Set up your Stripe webhook** to receive `checkout.session.completed` events.
4.  **After successful payment**, prompt the user via your `successUrl` page (or email) to submit their landing page URL.
5.  **Record and deliver feedback** via Loom video and a bullet-point summary via email within 24-48 hours.