# Vite + Tailwind CSS

A starter kit for my small personal projects requires Vite and Tailwind CSS.

## Installation

You can clone this project if you want.

```bash
git clone https://github.com/maliksvd/vite-tailwindcss.git
```

#### Or install the following dependencies.

Scaffolding Vite Project

```bash
yarn create vite
```

Add latest Tailwind CSS and its peer dependencies

```bash
yarn add -D tailwindcss postcss autoprefixer
```

Run the init command to generate Tailwind CSS file and PostCSS config file.

```bash
npx tailwindcss init -p
```

Edit the Tailwind CSS config file to add path to all of your template files.

```javascript
module.exports = {
  content: ['./index.html', './src/**/*.{vue,js,ts,jsx,tsx}'],
  theme: {
    extend: {},
  },
  plugins: [],
};
```

And finally add Prettier for Automatic Class Sorting with Prettier.

```bash
yarn add -D prettier prettier-plugin-tailwindcss
```

## Sources

- [Getting Started - Vite](https://vitejs.dev/guide/).
- [Install Tailwind CSS and Vite](https://tailwindcss.com/docs/guides/vite).
- [Automatic Class Sorting with Prettier](https://tailwindcss.com/blog/automatic-class-sorting-with-prettier).

## License

[MIT](https://choosealicense.com/licenses/mit/)
