# Astro Clerk

This is a simple project to demonstrate the use of the [Astro](https://astro.build/) and user accounts with [clerk](https://clerk.com/).

## Getting Started

To get started, you will need to create a Clerk account and have Astro installed for local development. Once you have created your clerk account, you will need to create a Clerk application.

Fork this repository and clone it to your local machine. Once you have cloned the repository, you will need to install the dependencies.

```bash
npm install
```

## Local Development .env

Create a `src/.env.local` file add the following environment variables.

```bash
PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
```

These can be found on the clerk dashboard in the api keys section.

## Running the project

To run the project locally, you can use the following command.

```bash
npm run dev
```

## SSR Adapter

This project uses the Vercel SSR adapter to allow for server-side rendering of the Clerk components.

## Deployment

This project is set up to be deployed to Vercel. The easiest way to do this is to push your project to a repository and import it into Vercel. Once you have imported the project, you will need to add the environment variables to the Vercel dashboard in the settings section.
