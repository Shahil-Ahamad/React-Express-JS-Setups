
<h1>To Setup Express Js </h1>

<h1>open terminal</h1>

```bash
mkdir <file_name>
```

![mkdir](https://github.com/user-attachments/assets/f0fa2995-20ed-474a-a435-d84a505a723b)

```bash
cd <file_name>
```

![cd](https://github.com/user-attachments/assets/303c77d7-f7a1-4840-843c-e26d77e25db3)

```bash
code .
```
<h1>code . will open your file in VS Code</h1>


<h2>It will download the node_module</h1>

```bash
npm init
```


```bash
npm install express
```

```bash
npm install express --no-save
```

<h2>It will Download tsconfig.json in your root<h2>

```bash
npm install -D typescript @types/node
```

```bash
npx tsc --init
```

<h1>There should be tsconfig.json file in your root.If not you done mistake </h1>

```bash
Go to the tsconfiig.json and search rootDir & outDir and un-comment them
write ./dist in outDir
  "outDir": "./dist", 

```
<h1>rootDir</h1>

![root](https://github.com/user-attachments/assets/62e1a033-c456-44de-9176-8847f58eefa6)

<h1>outDir</h1>

![ourdir](https://github.com/user-attachments/assets/95cf1b10-ed7d-4017-a578-0ee9952617dc)



<h1>Express Js is now setup</h1>

<h1>Now make folder in Vs code named src</h1>

<h2>After making folder src make anny file and run the file</h2>

<h1>To Run </h1>

```bash
npx tsc
node dist/src/file_name
```

