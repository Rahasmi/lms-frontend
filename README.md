# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

#LMS Frontend

### Setup instruction
1.Clone the project
...
    git clone https://github.com/Rahasmi/lms-frontend.git
...
2.move into the directory
...
    cd lms-frontend
...
3.install dependencies
...
    npm i
...

4.run the server
...
    npm run dev
...

### Setup instructions for tailwind
[tailwind official instruction doc](https://tailwindcss.com/docs/installation)

1. Install tailwindCSS
...
    npm install -D tailwindcss
...

2.Create tailwind config file
...
    npx tailwindcss init
...

3.Add file extensions to tailwind config file in the contents property
...
    "./src/**/*.{html,js,jsx,ts,tsx}"
...

4.Add the tailwind directives at the top of the 'index.css' file
...
    @tailwind base;
    @tailwind components;
    @tailwind utilities;
...