This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

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

You can start editing the page by modifying `app/page.js`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.

## The bugs you identified and fixed

1. Debugging layout.js

- Navigation links were missing the href attribute.
- Updated navigation links to use the Next.js <Link> component with correct attribute.

2. Fixing Data Fetching in page.js

- Fixed the wrong API URL.
- Removed pokemonList from dependency array, as it was causing an infinite loop.
- Added try-catch block for error handling

3. updated href in page.js

4. Added <Link> component to navigate back to home page.

5. Fixing the broken api and updated the API URL.

- added try-catch error handling for fetch request.

6. updated the correct property for pokemon images.

## Learned during the debugging process

I learned that small mistakes, like missing attributes or incorrect data, can cause big problems in an app.
Proper error handling is really important to make sure the app works well, even if something goes wrong.
I also realized that using the correct data and making sure links and routes are set up right is key to
making the app function smoothly.
