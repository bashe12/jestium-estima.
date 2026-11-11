# JESTIUM Enterprise Ecosystem — Frontend Prototype

## Project structure
- `index.html` — application shell and global layout
- `css/styles.css` — responsive enterprise design system
- `js/app.js` — application state, marketplace, ESTIMA and enterprise workflows

## Run
1. Extract the ZIP.
2. Open `index.html` in a modern browser.
3. For best local development experience, open the folder in VS Code and run it with the Live Server extension.

No build step is required.

## Demo interactions
- Portal switcher: Marketplace / ESTIMA Engine / Enterprise.
- Role selector: Buyer, Merchant, Service Provider, Engineer, Administrator.
- Demo OTP: `123456`.
- Marketplace: search, category filter, add to cart, single-seller cart rule, compare, RFQ, checkout and printable invoice.
- ESTIMA: edit takeoff quantities/rates, change pricing assumptions, create projects and print BPU/DQE/DPGF report previews.
- Enterprise: inventory creation, delivery rates, order workflow, provider plans, RFQ proposals, merchant verification and dispute decision simulation.

## Important prototype limitations
This is a client-side prototype. Data is persisted in browser localStorage. Authentication, OTP, payment, refunds, document storage, merchant verification, and platform administration are simulations. A production deployment requires a secure backend, database, authorization policies, audit logging, payment provider integration, server-side validation, and real document storage.

Product photography is loaded from Unsplash and requires an internet connection.
