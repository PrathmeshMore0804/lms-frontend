# LMS Frond-End

### Set Up Instructions

1. clone the project

```
    git clone https://github.com/PrathmeshMore0804/lms-frontend.git
```

2. move into directory

```
    cd lms-App
```

3. install dependecies

```
    npm i
```

4. run the server

```
    npm run dev
```

### set up instruction for tailwind

[official tailwind instruction doc ](https://tailwindcss.com/docs/guides/create-react-app)

1. install tailwind css

```
    npm install -D tailwindcss
```

2. create tailwind config file

```
    npx tailwindcss init
```

3. add file extension to tailwind config file in the content property

```
    "./src/**/*.{html,js,jsx,ts,tsx}"
```

4.  add the tailwind directives at the top of the `index.css`

```
   @tailwind base;
   @tailwind components;
   @tailwind utilities;
```

### add plugins and dependencies

```
    npm install @reduxjs/toolkit react-redux react-router-dom react-icons react-chartjs-2 chart.js daisyui axios react-hot-toast @tailwindcss/line-clamp
```
