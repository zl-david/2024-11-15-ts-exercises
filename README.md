## 01 New TS Project

Initialize project

```sh
mkdir 01-new-ts-project
cd 01-new-ts-project
npm init -y
```

Install TypeScript

```sh
npm install --save-dev typescript
```

Generate a tsconfig.json File

```sh
npx tsc --init
```

Open `tsconfig.json` and change out directory to './dist'

```json
{
  //...
  "outDir": "./dist"
  //...
}
```

Create a file `index.ts` in a `src` folder

```typescript
// src/index.ts
const message: string = "Hello, TypeScript!";
console.log(message);
```

Compile TypeScript

```sh
npx tsc
```

Execute

```sh
node dist/index.js
```

## 02 Basic Types

## 03 Classes
