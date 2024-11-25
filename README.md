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

[exercise.ts](./02-basic-types/exercise.ts)

## 03 Classes

[exercise.ts](./03-classes/exercise.ts)

## 04 Advanced Types

[exercise.ts](./04-advanced-types/exercise.ts)

## 05 More Generics

[https://github.com/zl-david/typescript-generics](https://github.com/zl-david/typescript-generics)

## 06 TsDD: Mini project

[exercise.ts](./06-tsdd/exercise.ts)

## 07 Generics, function overload & union types in React

[README.md](./07-generics-react/README.md)
