# NextJS 13 E-Commerce Project

Welcome to the NextJS 13 E-Commerce Project! This repository serves as the foundation for building a modern and scalable e-commerce website using Next.js 13. Whether you're a developer looking to contribute or an entrepreneur starting your online store, this project aims to provide you with a solid starting point.

## Getting Started

### Prerequisites

1. **Node.js**: Make sure you have Node.js installed. You can download it from [nodejs.org](https://nodejs.org/).

### Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/nextjs-ecommerce-project.git
    ```
2. Navigate to the project directory:

   ```bash
   cd nextjs-ecommerce-project
   ```
3. Install the dependencies:

   ```bash
   pnpm install
   ```
### Configuration

1. Create a `.env.local` file in the root directory of the project.
2. Add the following environment variables to the `.env.local` file:

   ```bash
   STRIPE_API_KEY=your-stripe-api-key
   STRIPE_WEBHOOK_SECRET=your-stripe-webhook-secret
   STRIPE_SUCCESS_URL=http://localhost:3000/success
   STRIPE_CANCEL_URL=http://localhost:3000/cancel
   ```

   > **Note:** Replace the values with your own Stripe API key and webhook secret.
   > **Note:** The success and cancel URLs are used to redirect the user after they complete the checkout process.

### Development

1. Create a new branch:

   ```bash
   git checkout -b your-branch-name
   ```
2. Make your changes.
3. Commit your changes:

   ```bash
   git commit -m "your commit message"
   ```
4. Push your changes to the remote repository:

   ```bash
    git push origin your-branch-name
    ```
5. Open a pull request on GitHub.
6. Wait for the pull request to be reviewed and merged.
7. Delete your branch.
8. Repeat.
9. Read the [Git documentation](https://git-scm.com/doc) to learn more about Git.

Production build:

```bash
pnpm build
```
### Features

- [x] Next.js 13
- [x] Tailwind CSS 2.2
- [x] Stripe Checkout
- [x] Stripe Webhooks
- [x] PNPM
- [x] Vercel
- [x] Git
- [x] GitHub

### Acknowledgments

- [Next.js](https://nextjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Stripe](https://stripe.com/)
- [PNPM](https://pnpm.io/)
- [Vercel](https://vercel.com/)
- [Git](https://git-scm.com/)