# Build a Supply Chain Optimizer
## Optimize an existing supply chain like a real operations leader
## prompt
You are an expert frontend developer, UX designer, game designer, and supply chain consultant.

Build a complete single-file HTML app named 'Supply Chain Builder'.

Design it so a complete beginner can understand supply chains. Before every decision, explain what the concept means, why it matters, and how it affects a business.

Requirements:

* Output ONLY one HTML file.
* React via CDN + Babel JSX.
* Plain HTML, CSS, and JavaScript only.
* No Tailwind, npm, backend, APIs, images, or external assets.
* Runs offline by opening the HTML file.
* No placeholders or incomplete features.

Flow:

1. Welcome screen introducing supply chains in simple language.
2. Generate a random company (industry, products, countries served, demand level).
3. Guide the player through building their supply chain by choosing:
   * Number of suppliers (single or multiple)
   * Factory location
   * Warehouse strategy
   * Transportation method (road, rail, sea, air)
   * Inventory strategy (low, balanced, high)
4. After every choice, explain the trade-offs in plain English.
5. Display live business metrics that update after each decision:
   * Cost
   * Delivery Speed
   * Risk
   * Customer Satisfaction
   * Sustainability
6. At the end, generate a dashboard with an Overall Supply Chain Score (0-100), strengths, weaknesses, biggest risk, and three practical improvements.

Design:

* Premium enterprise dashboard.
* Dark theme.
* Responsive.
* Smooth transitions.
* Rounded cards.
* Hover effects.
* Animated progress bars.
* Replay button.

Randomize company details each playthrough. Organize the app into reusable React components using useState. Ensure every button works and return ONLY the complete HTML inside one code block.
<img width="550" height="386" alt="image" src="https://github.com/user-attachments/assets/f7a19a95-7e0f-4fc5-bcd2-e0a7c7ef5097" />
