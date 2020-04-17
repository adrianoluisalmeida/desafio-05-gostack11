### :rocket: Desafio 05: Fundamentos Node.js GoStack 11.0
Neste desafio foi solicitada a criação de uma aplicação com typescript para
registrar entradas e saídas financeiras.


### Tecnologias utilizadas

- [Node.js](https://nodejs.org/en/)
- [TypeScript](https://www.typescriptlang.org/)
- [Jest](https://www.npmjs.com/package/jest)

Também foram utilizadas tecnologias para padronização de código, são elas:
prettier, eslint e editorconfig.

### Executando a aplicação

```js
yarn
yarn dev:server
```

**Para executar os testes:**

```js
yarn test
```

### :muscle: Endpoints


[GET] *http://localhost:3333/transaction*
```json
{
  "transactions": [
    {
      "id": "532330a5-f0e3-4115-8c6a-ed2f8a3f74e6",
      "title": "Frella",
      "value": 3000,
      "type": "income"
    },
    {
      "id": "1a099b7d-eac7-4781-8568-a63dabbfcb6b",
      "title": "Salário",
      "value": 3000,
      "type": "income"
    },
    {
      "id": "65034127-ef5d-49b7-9de1-42ee3c1195c4",
      "title": "Notebook",
      "value": 3000,
      "type": "outcome"
    }
  ],
  "balance": {
    "income": 6000,
    "outcome": 3000,
    "total": 3000
  }
}
```

[POST] *http://localhost:3333/transaction*
```json
{
  "title": "Salário",
  "value": 3000,
  "type": "outcome"
}
```




### :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.

---

<p align="center">Feito  por <strong>Adriano Almeida</p>
