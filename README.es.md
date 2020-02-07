# Template de Svelte con Tailwind

[![Svelte + Tailwind](https://i.imgur.com/qEDpxJj.png)](https://dev.to/erianvc/configurando-svelte-con-tailwind-52g9)
---
<br>

<p align="right"><a href="README.md"><img src="http://icons.iconarchive.com/icons/famfamfam/flag/16/us-icon.png"></a> / <a href="README.es.md"><img src="http://icons.iconarchive.com/icons/famfamfam/flag/16/es-icon.png"></a></p>

Este proyecto es un template para aplicaciones [Svelte](https://svelte.dev) con [TailwindCSS](https://tailwindcss.com/).

Para crear un nuevo proyecto basado en este template usando [degit](https://github.com/Rich-Harris/degit):

```bash
npx degit erianvc/svelte-tailwind svelte-app
cd svelte-app
```

*Tenga en cuenta que necesita tener [Node.js](https://nodejs.org) instalado.*

<br>

## Empezando

Instalar las dependencias...

```bash
cd svelte-app
npm install
```

...luego iniciar [Rollup](https://rollupjs.org):

```bash
npm run dev
```

Acceda al [localhost:5000](http://localhost:5000) ahí podrá ver su aplicación ejecutándose. Edite la los archivos en la carpeta `src`, salve los cambios, y eso recargará la página pusiendo apreciar los cambios realizados.

Por defecto, el servido solo responderá a peticiones del localhost. Para permitir conexiones desde otras computadoras, edite el comando `sirv` en package.json incluyendo la opción `--host 0.0.0.0`.
