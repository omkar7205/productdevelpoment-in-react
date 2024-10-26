enge Details:
1. Product Selection:
○ Display a list of products for users to select from.
○ Simulate product stock availability (e.g., 80% of products are in stock for any
warehouse).
2. Pincode Input:
○ Allow users to input a valid pincode.
○ Validate the pincode and associate it with the appropriate logistics provider.
3. Delivery Date Estimation Logic:
○ Use the pincode and provider to estimate the delivery date:
■ Provider A: Same-day if ordered before 5 PM and in stock.
■ Provider B: Same-day if ordered before 9 AM, next-day otherwise.
■ General Partners: Delivery within 2-5 days depending on the region.
4. Timer for Same-Day Delivery:
○ Add a visible countdown timer for Provider A and Provider B orders to
indicate how much time remains for qualifying for same-day delivery. This
should function similarly to Amazon's countdown timer.
5. Date and Time Awareness:
○ Ensure the application accurately considers the current date and time to
calculate delivery estimates.
6. Hosting Requirement:
○ Host the application on a platform like Vercel, Netlify, or any other suitable
hosting service.
○ Provide a URL where the application can be accessed and tested.
