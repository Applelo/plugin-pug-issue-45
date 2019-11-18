# How to reproduce

Install prettier and prettier/plugin-pug

```
npm i
```

Then open this project in VSCode and run Format Document with the Prettier plugin for VSCode. Single quotes are transformed into doubles quotes even with the singleQuote options. It's happen also with the command line options :

```
npx prettier --write '**/*.pug'
```