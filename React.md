<h1>To Setup React Js </h1>

<h1>open terminal</h1>

```bash
mkdir <file_name>
```

![mkdir](https://github.com/user-attachments/assets/f0fa2995-20ed-474a-a435-d84a505a723b)

```bash
cd <file_name>
```

![cd](https://github.com/user-attachments/assets/d180d613-f13e-406e-9ffd-aeee0a6ae172)

<h1>In Vite</h1>

```bah
npm create vite@latest
```

[text](https://github.com/user-attachments/assets/bfc8bdae-7e8d-4b1c-be2e-f4b02934f4e5)

<h2>After cd open file in VS-code</h2>

```bash
code .
```

![code](https://github.com/user-attachments/assets/e6edad96-0357-4a8f-b03e-2002b2a72f3a)

<h1>code . will open your file in VS Code</h1>

<h1>The file root should look like this⬇️⬇️</h1>

![file](https://github.com/user-attachments/assets/ae6691ad-73bf-4e7a-9ba0-8cb804210806)

<h1>THEN</h1>
<h2>Open terminal of VS Code </h2>

<h2>It will download node_module</h2>

```bash
npm install
```

![node_modue](https://github.com/user-attachments/assets/00ef97b7-e58c-4f4b-bdef-01892bfc146f)

<h1>For Styling Setup Tailwind CSS </h1>

<h2>In Terminal</h2>

```bash
npm install -D tailwindcss postcss autoprefixer
```

<h1>It will add tailwind.config.js file</h1>

```bash
npx tailwindcss init -p
```

![config](https://github.com/user-attachments/assets/2510f7a7-eae0-4394-b136-8d03f3adc76f)

<h1>In tailwind.config.js file Remove all code and paste the below code</h1>

```bash
/** @type {import('tailwindcss').Config} */
export default {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

<h1>In index.css remove all code and paste the below code</h1>

```bash
@tailwind base;
@tailwind components;
@tailwind utilities;
```

![index](https://github.com/user-attachments/assets/c82f3475-18e2-423e-90c1-73546107ef5f)

<h1>Remove all code in app.css also</h1>

<h1>Then in app.jsx </h1>

[text](https://github.com/user-attachments/assets/bb306d5c-5c6d-4a8c-8bbd-e50b1c90adfd)

<h1><b>For Running React File.</b>In Terminal</h1>

```bash
npm run dev
```

![run](https://github.com/user-attachments/assets/938620ae-f49f-4c58-b87b-7121b2b76c06)

<h1>After that click the local host</h1>

![local](https://github.com/user-attachments/assets/42e0c21d-98de-4050-ac92-56b3105b4c05)

<h1>your browser should be open</h1>

![Screenshot 2024-09-20 100857](https://github.com/user-attachments/assets/b62716c3-1da3-41a8-b4f9-b3310a400a7c)
