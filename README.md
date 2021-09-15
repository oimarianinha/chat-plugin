## Tecnologias utilizadas

- [Node.js](https://nodejs.org/)
- [Socket.io](https://socket.io/)
- [Typescript](https://www.typescriptlang.org/)
- [Express](https://expressjs.com/)

## Projeto

O chat é um plugin para atendimento dos clientes em tempo real.

## Como usar?

Abra o terminal na pasta do projeto e instale as dependencias:
```sh
yarn
```

Rode o comando abaixo para criação do arquivo `database.sqlite` dentro da pasta `src/database`:
```sh
yarn typeorm migration:run
```

Para iniciar a aplicação: 
```sh
yarn dev
```

**1. Visão Cliente**
```sh
http://localhost:3333/pages/client
```
**2. Visão Administrador**
```sh
http://localhost:3333/pages/admin
```

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
