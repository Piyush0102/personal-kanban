# Personal Kanban

This Kanban board is a visual project management tool that helps you manage tasks and workflows efficiently. It provides a visual representation of work items, allowing you to track progress and prioritize tasks easily. <br>

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Development](#development)
4. [Deployment](#deployment)

## Introduction
The Kanban board is a versatile and powerful tool that has revolutionized how to manage projects and tasks. Originally developed by Toyota in the 1940s, Kanban has evolved into a widely adopted project management methodology that emphasizes efficiency, collaboration, and continuous improvement. <br>
At its core, a Kanban board is a visual representation of your work process. It allows you to organize tasks, track their progress, and ensure a steady flow of work from start to finish. Whether you're working on software development, marketing campaigns, product manufacturing, or virtually any other field, a Kanban board can help you streamline your processes, reduce bottlenecks, and enhance overall productivity. <br>
The essence of a Kanban board lies in its simplicity. It consists of columns that represent different stages of your workflow, and within these columns are task cards that represent individual work items. By moving these task cards from one column to the next as they progress, you gain a clear understanding of your work's status and can easily identify areas that need attention.

## Features
A few of the things you can do with Personal Kanban :

- Add, Edit, Delete Columns <br>
- Move Columns <br>
- Add, Edit, Delete Records <br>
- Move Records <br>
- Clear Board

## Development
The application is scaffolded using React.js, Vite.js and Typescript templating. <br>

To run the application locally you can follow the steps below :

- Using npm
```
1: git clone https://github.com/Piyush0102/personal-kanban
2: cd personal-kanban
3: npm install
4: npm run build
5: npm run dev
```


Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

 ### Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
   parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
   },
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list

## Deployment
The project is hosted using Netlify. 
You can view the deployment of this project by clicking on the below link 👇🏼👇🏼 <br>
https://personal-kanban1.netlify.app
