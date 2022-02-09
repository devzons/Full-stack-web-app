# create-svelte

Everything you need to build a Svelte project, powered by [`create-svelte`](https://github.com/sveltejs/kit/tree/master/packages/create-svelte).

## Creating a project

If you're seeing this, you've probably already done this step. Congrats!

```bash
# create a new project in the current directory
npm init svelte@next

# create a new project in my-app
npm init svelte@next my-app
```

> Note: the `@next` is temporary

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

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs#adapters) for your target environment.

## Full-stack Web Development

- Gitpod https://www.gitpod.io/
- Svelte (https://svelte.dev/) - Frontend
- SvelteKit (https://kit.svelte.dev/) - Host the app, API
- Prisma (https://www.prisma.io/) - SQL queries
- Postgres (https://www.postgresql.org/) - database
- Vercel (https://vercel.com/) - Prisma
- Railway (https://railway.app/) - Postgres

### Architecture

![Alt Project Architecture] (https://user-images.githubusercontent.com/788827/145879564-e7dc42d6-3055-492b-95d7-902e9a5fad96.png)

### Install sveltekit

### Configure Gitpod

```
https://gitpod.io/new

# create .gitpod.yml on root,

tasks:
  - init: npm install
    command: npm run dev
```
