# BeFit!

## Starting up

### Clone repo

```git
  git clone https://github.com/Adriano1324/BeFitFrontend main
```

### Install app dependencies 


```npm
  npm install
```

### Run app localy

Make sure you are in correct directory

```npm
  npm run dev
```

## App src directory structure 

```
src
│   main.scss
│   main.tsx
│   vite-env.d.ts
│   
├───assets
│       react.svg
│       vite.svg
│       
└───components
    └───App
            App.scss
            App.tsx
```

Every component must have own catalog with this same name as component

Every child component must have be created in this directory which it's parent (f.e. LoginForm component is created at App directory.)
