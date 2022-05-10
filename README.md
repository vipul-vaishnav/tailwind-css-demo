# Tailwind CSS Demo

A simple project made using css framework Tailwind CSS

## Authors

- [@vipul-vaishnav](https://www.github.com/vipul-vaishnav)

## Tech Stack

**CSS Framework:** TailwindCSS

## Installation

Installation requires [Node.js](https://nodejs.org/) to run.

Install the dependencies and devDependencies and start the server.

Create a new directory and follow the steps :-

```sh
cd <Directory Name>
npm init --yes
npm install -D tailwindcss postcss autoprefixer vite
```

"npm inti --yes" initialises the directory as a node.js project

"npm install -D tailwindcss postcss autoprefixer vite" installs the required dependencies(packages)

```sh
npx tailwindcss init -p
```

create a css file "input.css", add it to your html and edit it with this content:

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

In the "tailwind.config.js" file replace **content: []**, with **content: ["*"]**,

In the "package.json" file add a new script

```npm-script
"start": "vite"
```

Run the script to start a dev server

```sh
npm run start
```

## Features

- Faster CSS Styling Process
- Control Over Styling
- Tailwind helps you keep your final CSS as small as possible.
- An excellent solution for developers familiar with CSS who want to speed up the creation and design process in the long run.
