# Svelte with Tailwind Template

![Svelte + Tailwind](https://i.imgur.com/qEDpxJj.png)
---
<br>

<p align="right"><a href="README.md"><img src="http://icons.iconarchive.com/icons/famfamfam/flag/16/us-icon.png"></a> / <a href="README.es.md"><img src="http://icons.iconarchive.com/icons/famfamfam/flag/16/es-icon.png"></a></p>

This is a project template for [Svelte](https://svelte.dev) apps with [TailwindCSS](https://tailwindcss.com/).

To create a new project based on this template using [degit](https://github.com/Rich-Harris/degit):

```bash
npx degit erianvc/svelte-tailwind svelte-app
cd svelte-app
```

*Note that you will need to have [Node.js](https://nodejs.org) installed.*

<br>

## Get started

Install the dependencies...

```bash
cd svelte-app
npm install
```

...then start [Rollup](https://rollupjs.org):

```bash
npm run dev
```

Navigate to [localhost:5000](http://localhost:5000). You should see your app running. Edit a component file in `src`, save it, and reload the page to see your changes.

By default, the server will only respond to requests from localhost. To allow connections from other computers, edit the `sirv` commands in package.json to include the option `--host 0.0.0.0`.

*Note if you modify the `tailwind.css` or `tailwind.config.js` file you have to down the server and resend the `npm run dev` command.*
