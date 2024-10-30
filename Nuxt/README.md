# Install module

## 💩 tailwincss
```bash
# install module
npx nuxi@latest module add tailwindcss

# add tailwind.config.js file
npx tailwindcss init
```

If you want to make tailwincss class in global

1. create file css in ..

    - assets
    - css
        - main.css

2. add tailwind directives in main.css
    ```bash
    @tailwind base;
    @tailwind components;
    @tailwind utilities;
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
