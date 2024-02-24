# ESLint Config

> [!NOTE]  
> As configurações aqui presentes foram baseadas e adaptadas com base no [repositório de configurações da Rocketseat](https://github.com/Rocketseat/eslint-config-rocketseat).

## ⚙️ Como instalar

Instale as dependências:

Com NPM:

```
npm i -D eslint @theduardomaciel/eslint-config
```

Com PNPM:

```
pnpm add -D eslint @theduardomaciel/eslint-config
```

Com BUN:

```
bun add -D eslint @theduardomaciel/eslint-config
```

### Next.js

Dentro de `.eslintrc.json` insira

```
{
  "extends": [
    "@theduardomaciel/eslint-config/next",
    "next/core-web-vitals"
  ]
}
```

### React

Dentro de `.eslintrc.json` insira

```
{
  "extends": "@theduardomaciel/eslint-config/react"
}
```

### Node.js

Dentro de `.eslintrc.json` insira

```
{
  "extends": "@theduardomaciel/eslint-config/node"
}
```
