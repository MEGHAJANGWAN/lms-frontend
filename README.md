# LMS frontend

### setup instruction

1. clone the project
   ...
   git clone -: https://github.com/MEGHAJANGWAN/lms-frontend
   ...

2. Move into the directory
   ...
   cd lms-frontend
   ...

3. install dependencies
   ...
   npm i
   ...

4. run the server
   ...
   npm run dev
   ...

   ## install tailwind

   1. npm install -D tailwindcss@3 postcss autoprefixer
      npx tailwindcss init -p

5. configure template paths

## tailwind.config.js

     content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",

],

3. Add the Tailwind directives to your CSS

## index.css

@tailwind base;
@tailwind components;
@tailwind utilities;

4. Start your build process

npm run dev

### adding pluggins and dependencies

npm install @reduxjs/toolkit react-redux react-router-dom react-icons react-chartjs-2 chart.js daisyui axios react-hot-toast @tailwindcss/line-clamp

### configure auto import sort eslint
1. install simple import sort
...
npm i eslint-plugin-simple-import-sort
...

2. add rule in 'eslint.cjs'
...
 'simple-import-sort/imports': 'error'
...

3. add simple-import sort plugin in '.eslint.cjs'
...
plugins: ['react-refresh', 'simple-import-sort']
...

4. To enable auto import sort on file save in vscode
  - Open 'setting.json'
  - add the following config
...
"editor.codeActionsOnSave": {
   "source.fixAll.eslint": true
}
...


