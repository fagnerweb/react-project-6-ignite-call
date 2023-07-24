# Ignite Call
npx create-next-app@latest --use-npm

`usar o page router`

`npm i @ignite-ui/react@latest`

## Eslint
`npm i @rocketseat/eslint-config`

```bash
{
  "extends": [
    "@rocketseat/eslint-config/react",
    "next/core-web-vitals"
  ]
}
```

# Google oAuth com Next Auth
npm install next-auth


## Error
ao rodar o comando `npx prisma migrate dev` aparece uma mensagem de erro que diz:

```bash
EPERM: operation not permitted, unlink
'C:\Users\fagne\curso\rocketseat\react\projeto-6\ignite-call\node_modu
les\.prisma\client\query_engine-windows.dll.node'.*

Solução:

Excluir o arquivo query_engine-windows.dll.node
```