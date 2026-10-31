
# VADI — Everything. Simply Yours.

<p align="center">
  <strong>A modern, premium shopping experience built for everyday style.</strong>
</p>

<p align="center">
  Discover fashion, footwear, watches, gadgets, collectibles, and more — all in one place.
</p>

---

## About VADI

**VADI** is a modern e-commerce platform designed to deliver a smooth, responsive, and visually engaging shopping experience.

The platform brings together multiple product categories through a unified storefront, with a dedicated administration panel for managing products, inventory, homepage sections, offers, and customer orders.

Our vision is simple:

> Everything. Simply Yours.

## Features

### Customer Storefront
- Premium, responsive homepage
- Dedicated product categories and collection pages
- Product search and category filters
- Product details, images, pricing, and inventory status
- Shopping cart and wishlist
- Customer authentication and account management
- Order and checkout experience
- Responsive desktop and mobile layouts

### Product Categories
VADI brings multiple shopping categories together, including:

- Shoes & Sneakers
- Watches & Accessories
- Smart Gadgets & Audio
- Bags, Packs & Luggage
- Posters & Art Prints
- Toys & RC Hobby
- Marvel, DC & Anime Collections
- Hot Wheels Garage
- Neon Lights & Home Décor

### Admin Panel
- Product creation, editing, and management
- Category and subcategory management
- Inventory and storefront availability controls
- Homepage section visibility and ordering
- Product Agent and manual product uploads
- Offer and BOGO deal management
- Order and customer management
- Storefront configuration

### Performance & Experience
- Responsive design
- Optimized product presentation
- Smooth animations and interactive UI
- Glassmorphism and modern visual effects
- Performance-focused loading and rendering

---

## Tech Stack

| Technology | Purpose |
|---|---|
| Next.js | Web application framework |
| TypeScript | Type-safe development |
| React | User interface |
| Supabase | Database, authentication, and backend services |
| Vercel | Deployment and hosting |
| Git & GitHub | Version control |

---

## Getting Started

Follow these steps to run the project locally.

### Prerequisites

Make sure you have installed:

- Node.js
- npm
- Git

### 1. Clone the Repository

```bash
git clone YOUR_REPOSITORY_URL
cd YOUR_PROJECT_FOLDER
```

Replace the repository URL and folder name with your actual project details.

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Environment Variables

Create a `.env.local` file in the project root.

Add the environment variables required by your project. For example:

```env
NEXT_PUBLIC_SUPABASE_URL=your_supabase_project_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
```

Use the exact variable names expected by your application.

**Security:** Never commit `.env.local`, service-role keys, payment gateway secrets, or other private credentials to GitHub. Keep secret keys on the server side.

### 4. Start the Development Server

```bash
npm run dev
```

Open the following address in your browser:

```text
http://localhost:3000
```

---

## Project Structure

The exact structure may vary depending on the current implementation.

```text
VADI/
├── public/             # Static assets and images
├── src/
│   ├── app/            # Application routes and pages
│   ├── components/     # Reusable UI components
│   ├── lib/             # Shared utilities and integrations
│   └── types/           # TypeScript types
├── .env.local          # Local environment variables
├── package.json
├── tsconfig.json
└── README.md
```

---

## Deployment

VADI is designed to be deployed using **Vercel**.

1. Push the project to GitHub.
2. Import the repository into Vercel.
3. Configure the required environment variables.
4. Deploy the application.
5. Verify the storefront, admin panel, and Supabase connectivity.

For production deployments, ensure that all secrets are configured securely and that database access policies are properly enabled.

---

## Development Notes

- Keep the storefront and admin panel connected to the same intended data source.
- Preserve existing product and order data during development.
- Verify database schema changes before applying migrations.
- Test homepage section visibility and ordering after admin updates.
- Test customer-facing features before deploying changes.

---

## Contributing

Contributions and improvements are welcome.

1. Fork the repository.
2. Create a feature branch.
3. Make your changes.
4. Test your implementation.
5. Submit a pull request.

---

## Project

**VADI — Everything. Simply Yours.**

A modern shopping destination built to bring style, technology, and collectibles together in one seamless experience.
