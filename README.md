## 1. Install the Dependencies

https://tailwindcss-react-native.vercel.app/installation

npm install tailwindcss-react-native
npm install --save-dev tailwindcss

## 2. Setup Tailwindcss

Create a tailwind.config.js file with the content section configured to include the paths to all 
your components and any other source files that contain Tailwind class names.

// tailwind.config.js
module.exports = {
  content: [
    "./screens/**/*.{js,ts,jsx,tsx}",
    "./pages/**/*.{js,ts,jsx,tsx}",
    "./components/**/*.{js,ts,jsx,tsx}",
  ],
  // ...
};

## 3. Setting up React Native Navigation
https://reactnavigation.org/docs/getting-started/




