# create-svelte

Everything you need to build a Svelte project, powered by [`create-svelte`](https://github.com/sveltejs/kit/tree/master/packages/create-svelte).

In this SvelteKit:
 - Vite (module bundler) 
 - ESLint for code linting
 - Prettier for code formatting
 - Playwright for browser testing
 - Vitest for unit testing
 - Typescript for type checking

## Creating a project

Node deets:
- Node.js v18.16.0 to /usr/local/bin/node
- npm v9.5.1 to /usr/local/bin/npm

Make sure that /usr/local/bin is in your $PATH.
```bash
nvm install 18.16.0
```

If you're seeing this, you've probably already done this step. Congrats!

```bash
# create a new project in the current directory
npm create svelte@latest

# create a new project in my-app
npm create svelte@latest my-app
```

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.
