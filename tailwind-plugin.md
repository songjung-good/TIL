
# tailwind의 공식 플러그인

## 

npm install -D prettier-plugin-tailwindcss

npm install -D @tailwindcss/typography
npm install -D @tailwindcss/forms
npm install -D @tailwindcss/aspect-ratio
npm install @tailwindcss/container-queries


##
```javascript
export default {
  content: ["./index.html", "./src/**/*.{js,ts,jsx,tsx}"],
  theme: {
    extend: {},
  },
  corePlugins: {
    aspectRatio: false,
  },
  plugins: [
    require("@tailwindcss/typography"),
    require("@tailwindcss/forms"),
    require("@tailwindcss/container-queries"),
    require("@tailwindcss/aspect-ratio"),
  ],
};
```