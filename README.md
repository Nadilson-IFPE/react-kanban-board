# Aviso àqueles que clonarem este código-fonte

Este código foi escrito a partir do tutorial "React Kanban Board | React and Tailwind Css Task Management App", cujo endereço é: https://www.youtube.com/watch?v=yU7U5fpExxs

Por se tratar de um excelente tutorial, eu resolvi seguir o passo-a-passo.

--------------------

# Warning to those who clone this source code

This code was written from the tutorial "React Kanban Board | React and Tailwind Css Task Management App", whose address is: https://www.youtube.com/watch?v=yU7U5fpExxs

Because it was an excellent tutorial, I decided to follow it step-by-step.


--------------------

# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default {
  // other rules...
  parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
  },
}
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
