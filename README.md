# Svelte Template! It has everything for me!

powered by [`sv`](https://github.com/sveltejs/cli).

It's literally empty project but with every single thing installed. 
So i don't have to run `npx sv create .` and re-download everything again.

## Stack?

- MySQLv2
- Bun runtime
- Everything Svelte want me to try (Storybook, Paraglide, Drizzle etc.)
- Typescript!

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

> To deploy your app, you may need to install an [adapter](https://svelte.dev/docs/kit/adapters) for your target environment.

## Drizzle

- You will need to set DATABASE_URL in your production environment  │
│  - Run bun run db:start to start the docker container                │
│  - Run bun run db:push to update your database schema    

## Lucia
│  - Run bun run db:push to update your database schema                │
│  - Visit /demo/lucia route to view the demo     

## Paraglide
│  paraglide:                                                          │
│  - Edit your messages in messages/en.json                            │
│  - Consider installing the Sherlock IDE Extension                    │
│  - Visit /demo/paraglide route to view the demo     
