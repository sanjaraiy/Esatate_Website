# Estate Web Application

## Create React App Using Vite :-
```
npm create vite@latest
```
## Install Node-Modules Packages :-
```
npm i
```
## Install Tailwind CSS :-
```
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

## Configure your template paths :-
```
export default {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

## Add the Tailwind directives to your CSS :-
```
@tailwind base;
@tailwind components;
@tailwind utilities;
```


