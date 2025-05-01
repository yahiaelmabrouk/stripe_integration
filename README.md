# Stripe Checkout Example

This is a simple Node.js and Express application demonstrating Stripe Checkout integration for a shopping cart. Users can view a cart, proceed to checkout, and see success or cancellation pages after payment.

## Features

- Shopping cart UI with sample items
- Stripe Checkout integration for payments
- Success and cancel pages
- EJS templating

## Requirements

- Node.js (v14+ recommended)
- A Stripe account and API keys

## Setup

1. **Clone the repository:**

   ```sh
   git clone https://github.com/yahiaelmabrouk/stripe_integration.git
   cd str
   ```

2. **Install dependencies:**

   ```sh
   npm install
   ```

3. **Create a `.env` file in the project root:**

   ```
   STRIPE_SECRET_KEY=your_stripe_secret_key
   BASE_URL=http://localhost:3000
   PORT=3000
   ```

4. **Run the app:**

   ```sh
   node index.js
   ```

5. **Open your browser and go to:**
   ```
   http://localhost:3000
   ```

## Project Structure

- `index.js` - Main server file, handles routes and Stripe integration
- `views/` - EJS templates for UI
- `.env` - Environment variables (not committed)
- `.gitignore` - Common ignores for Node.js and Python
