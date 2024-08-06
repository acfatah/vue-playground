# Vite + Vue 3 + Tailwindcss Playground

## Features

- ⚡️ [Vite 2](https://github.com/vitejs/vite), [ESBuild](https://github.com/evanw/esbuild), [Vue 3](https://github.com/vuejs/vue-next)

- <img src="https://th.bing.com/th?id=ODLS.095f9b22-a70b-47ed-bdb1-070466f08dc4&w=32&h=32&qlt=90&pcl=fffffa&o=6&pid=1.2" height="16" width="16" alt="Tailwindcss Icon" class="rms_img" data-bm="42">&nbsp; [Tailwind CSS](https://tailwindcss.com/)

- <img src="https://th.bing.com/th?id=ODLS.3408c44a-9dc6-431c-ab53-7985c9dee8e7&amp;w=32&amp;h=32&amp;qlt=90&amp;pcl=fffffa&amp;o=6&amp;pid=1.2" height="16" width="16" alt="Global web icon" class="rms_img" data-bm="52"> &nbsp; [ESLint](https://eslint.org/) with [@antfu/eslint-config](https://github.com/antfu/eslint-config)

## Pre-installed Packages

### UI Frameworks

- [TailwindCSS](https://tailwindcss.com/)
  - [TailwindCSS Aspect Ratio](https://github.com/tailwindlabs/tailwindcss-aspect-ratio)
  - [TailwindCSS Forms](https://github.com/tailwindlabs/tailwindcss-forms)
  - [TailwindCSS Typography](https://github.com/tailwindlabs/tailwindcss-typography)

### Plugins

- [Unpluggin Vue Components](https://github.com/unplugin/unplugin-vue-components)

### Linting and Coding Style

- Use Composition API with [`<script setup>` SFC syntax](https://github.com/vuejs/rfcs/pull/227). Check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

- Auto formating using [Antony Fu ESLint config styling](https://github.com/antfu/eslint-config?tab=readme-ov-file#antfueslint-config)

### Dev tools

- [Vue DevTools](https://devtools-next.vuejs.org/)
- [Chrome Extension](https://chromewebstore.google.com/detail/vuejs-devtools/iaajmlceplecbljialhhkmedjlpdblhp)

## Usage

```bash
npx degit acfatah/vue-playground my-vue-component && \
  cd my-vue-component && \
  npm install
```

### Checklist

When you use this template, try follow the checklist to update your info properly

- [ ] Rename `name` field in `package.json`
- [ ] Change the author name in `LICENSE`
- [ ] Change the title in `App.vue`
- [ ] Change the favicon in `public`
- [ ] Remove the `.github` folder which may contains unrelevant info
- [ ] Clean up this README

### Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/) + [Vue - Official](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (previously Volar) and disable Vetur

- [VS Code Extensions](./.vscode/extensions.json)
  - [Vite](https://marketplace.visualstudio.com/items?itemName=antfu.vite) - Fire up Vite server automatically
  - [Volar](https://marketplace.visualstudio.com/items?itemName=johnsoncodehk.volar) - Vue 3 `<script setup>` IDE support
  - [TailwindCSS Intellisense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss) - IDE support for Tailwind CSS
  - [i18n Ally](https://marketplace.visualstudio.com/items?itemName=lokalise.i18n-ally) - All in one i18n support

### Development

Just run and visit http://localhost:5173

> The port number may be different

```bash
npm run dev
```

### Other Available Scripts

- `npm run lint`: Lint files
- `npm run lint:fix`: Lint files and fix them
- `npm run update`: Update dependencies according to [semver](https://semver.org/)
