## Project Details

Pantry Pal is a one-night-project to see if I could accomplish a working proof of concept for a web-application. 



## Features

- Suggests meals based on your current inventory.
- Inventory input, Persistent
- Meal details page

## Checklist
- [x] Project Setup
  - [x] Setup dependencies
  - [x] Setup project structure
  - [x] Setup prettier
  - [x] Setup Linting
  - [x] Setup Deployment
- [ ] Onboarding Page
  - [ ] Create a page where users input their available ingredients
  - [ ] Store ingredient list using Zustand
  - [ ] Allow users to add, edit, and remove ingredients
- [ ] Meal Suggestion Page
  - [ ] Fetch meal suggestions based on ingredients
  - [ ] Use a simple JSON database or a meal API (e.g., Spoonacular)
  - [ ] Display meal suggestions with images and descriptions
- [ ] Meal Details Page
  - [ ] Show a basic recipe or steps for preparing the meal


This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
