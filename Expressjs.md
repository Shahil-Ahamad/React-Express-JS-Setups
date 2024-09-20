
<h1>To Setup Express Js </h1>

```bash
open terminal

mkdir <file_name>
cd <file_name>
npm init
```
<h1>It should download node_modules in your root</h1>

```bash
npm install express
```

```bash
npm install express --no-save
```

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

<h1>Express Js is now setup</h1>
<h1>To Run </h1>
```bash
npx tsc
node dist/src/file_name
```

