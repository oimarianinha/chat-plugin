## Tecnologias utilizadas

- [Node.js](https://nodejs.org/)
- [Socket.io](https://socket.io/)
- [Typescript](https://www.typescriptlang.org/)
- [Express](https://expressjs.com/)

## Projeto

O chat é um plugin para atendimento dos clientes em tempo real.

## Como usar?

Abra um terminal de sua preferência e caso não tenha o arquivo `database.sqlite` dentro da pasta `src/database`, rode o comando abaixo:
```sh
yarn typeorm migration:run
```
Para iniciar a aplicação: 
```sh
yarn dev
```

Por fim, a aplicação estará disponível em `http://localhost:3333`

## Ideias de melhorias
- [ ] Validar emails
- [ ] Validar campos vazios
- [ ] Adicionar botão para finalizar atendimento
- [ ] Alterar layout do gerenciamento de atendimento
- [ ] Criar aba para histórico de atendimento
- [ ] Implementar avaliação ao final do atendimento

## Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---
