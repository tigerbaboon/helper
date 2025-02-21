# Install module

## 💩 tailwincss V4

1. install with `yarn add tailwindcss @tailwindcss/vite`

2. config vite plugin
```bash
import tailwindcss from "@tailwindcss/vite";
export default defineNuxtConfig({
  compatibilityDate: "2024-11-01",
  devtools: { enabled: true },
  vite: {
    plugins: [
      tailwindcss(),
    ],
  },
});
```

If you want to make tailwincss class in global

1. create file css in ..

    - assets
    - css
        - main.css

2. add tailwind directives in main.css
    ```bash
    @import "tailwindcss";
    ```
3. and in nuxt.config.ts file add path css in ..
    ```bash
    css: ["~/assets/css/main.css"],
    ```

## 💩 icon

```bash
# install module
npx nuxi module add icon
```

🔗 [Document more icon](https://icones.js.org/)

```bash
# example

<Icon name="uil:github" style="color: black" />

# name="collection name : icon name"
```

## 💩 pinia

```bash
# install module
npx nuxi@latest module add pinia
```

## 💩 axios

```bash
# install axios
npm install @nuxtjs/axios
```
