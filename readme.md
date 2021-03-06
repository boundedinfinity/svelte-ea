# Reference

- https://medium.com/mkdir-awesome/how-to-use-npm-link-to-create-a-sveltekit-component-library-97e9a66817fc
- https://kit.svelte.dev/docs#packaging

## Creating a project

```bash
mkdir my-app
cd my-app
npm init svelte@next
npx svelte-add@latest tailwindcss
npm install -D svelte2tsx
```

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

Before creating a production version of your app, install an [adapter](https://kit.svelte.dev/docs#adapters) for your target environment. Then:

```bash
npm run build
```

> You can preview the built app with `npm run preview`, regardless of whether you installed an adapter. This should _not_ be used to serve your app in production.
