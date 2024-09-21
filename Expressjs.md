
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

![code](https://github.com/user-attachments/assets/6210ccc3-395c-4c37-95f2-de2729fb7715)


<h1>code . will open your file in VS Code</h1>


<h2>It will download the packag.json file</h1>

(https://github.com/user-attachments/assets/9cc8c1af-5b4a-4ab9-802c-e92ce18f6fa1)

```bash
npm init
```



![package](https://github.com/user-attachments/assets/16788e42-1681-4ef4-ab97-9732f69a06b5)

<h2>It will download the node_module folder</h1>

```bash
npm install express
```

![node_modue](https://github.com/user-attachments/assets/340d417b-b1ab-4161-af6b-e9f7c9d39a5a)


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

![tsconfig](https://github.com/user-attachments/assets/df5cbab9-a2b5-4155-a65b-a7256cb91bd4)




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

<h2>After making folder src make any file and run the file</h2>

<h1>To Run </h1>

```bash
npx tsc
node dist/src/file_name
```

