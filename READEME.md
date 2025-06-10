# App

GymPass Style app.

## RFs (Requisitos funcionais)

- [ ] Deve ser possível se cadastrar;
- [ ] Deve ser possível se autenticar;
- [ ] Deve ser possível obter o perfil de um usuário logado;
- [ ] Deve ser possível obter o número de ckeck-ins realizados pelo usuário logado;
- [ ] Deve ser possível o usuário obter seu histórico de check-ins;
- [ ] Deve ser possivel o usuario buscar acadêmias proximas;
- [ ] Deve ser possível o usuário buscar uma acadêmias pelo nome;
- [ ] Deve ser possível realizar check-in na acadêmia;
- [ ] Deve ser possível validar o check-in de um usuário;
- [ ] Deve ser possível cadastrar uma acadêmia;

## RNs (Regras de negócios)

- [ ] O usuário não deve poder se cadastrar um e-mail duplicado;
- [ ] O usuário não pode fazer 2 check-ins no mesmo dia;
- [ ] O usuário não pode fazer check-in se não estiver perto (100m) da acadêmia;
- [ ] O check-in só pode ser validade até 20 minutos após criado;
- [ ] O check-in só pode ser validado por Admins;
- [ ] Acadêmia só pode ser cadastrado por Admins

## RNFs (Requisitos não funcionais)

- [ ] A senha do user precisa estar criptografada;
- [ ] Os dados da aplicação precisam estar persistidos em um banco de dados PostgreSQL;
- [ ] Todas as listas de dados precisam estar paginadas com 20 itens por página;
- [ ] O usuário deve ser identificado por um JWT;
