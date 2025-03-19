# APP
GymPass style app.

## RFs (Requisitos Funcionais) O que o user pode fazer?
- [ ] Deve ser possível se cadastrar;
 DEve ser possível se autenticar;
- [ ] Deve ser possível obter o perfil de um usuário logado;
- [ ]  Deve ser possível obter o número de check-ins realizados pelo usuário logado;
- [ ]  Deve ser possível o usuário obter seu histórico de check-ins;
- [ ]  Deve ser possível o usuário buscar academias próximas;
- [ ]  Deve ser possível o usuário buscar academias pelo nome;
- [ ]  Deve ser possível o usuário realizar check-in em uma academia;
- [ ]  Deve ser possível validar o check-in de um usuário;
- [ ]  Deve ser possível cadastrar uma academia;

## RNs (Regras de Negócio) Sempre associada ao requisto funcional! Condições!
- [ ] O usuário não deve poder se cadastrar com um e-mal duplicado;
- [ ] O usuário não pode fazer 2 check-ins no mesmo dia;
- [ ] O usuário não pode fazer check-in se não estiver perto da academia (100m);
- [ ] O check-in só pode ser validado após 20 minutos após criado;
- [ ]O check-in só pode ser validado por administradores;
- [ ] A academia só poder ser cadastrada por administradores;
## RNFs (Requisitos não-funcionais)
- [ ] A senha do usuário precisa estar criptografada;
- [ ] Os dados da aplicação precisam estar persistidos em um BD PostgreSQL;
- [ ] Todas as listas de dados precisam estar paginadas com 2 itens por página;
- [ ] O usuário deve ser identificado por um JWT (JSON Web Token);