# NextJS Contact Form

This simple Contact Form is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app), showcasing the NextJS functions a bit.

## Tech Stack

- NextJS 13.5.6
- MongoDB
- Tailwind CSS

## Getting Started

Firstly, pull down the repo from https://github.com/marcuszou/nextjs-contact-form.git

Secondly, open VS Code, install the extension of "MongoDB for VS Code", then open terminal and run the command:

```
npm install
```

Thirdly, go to https://cloud.mongodb.com and create a free-tier MongoDB project:

- name the project: "contact_db" or anything you like

- then create a deployment under free-tier ("M0"), then create a user with default password (__PLEASE__ write/copy down the password since we need it later)

- enter "__0.0.0.0__" as your IP Access List (allows everyone to connect), the click "__Finish and Close__" button

- Go to "__Overview__" page and click "__CONNECT__" button, then select "__MongoDB for VS Code__", copy the connection string

- create a __.env__ file in the project folder and fill the contents as below:

  ```
  MONGODB_URI=mongodb+srv://<username>:<password>@cluster0.hsqoyc4.mongodb.net/contact_db
  ```

- fill the \<username> and the \<password> with what you copied down previously.

Fourthly, run the development server:

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

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

## The End