### Requisitos

- [x] Deve ser possível criar uma conta
- [x] Deve ser possível buscar o extrato bancário do cliente 
- [x] Deve ser possível realizar uma depósito 
- [x] Deve ser possível realizar um saque
- [x] Deve ser possível buscar o extrato do cliente por data
- [x] Deve ser possível atualizar dados da conta do cliente
- [x] Deve ser possível obter dados da conta do cliente
- [x] Deve ser possível deletar uma conta

## Regras de negócio

- [x] Não deve ser possível cadastrar uma conta com CPF já existente
- [x] Não deve ser possível buscar extrato em uma conta não existente
- [x] Não deve ser possível fazer depósito em uma conta não existente
- [x] Não deve ser possível fazer saque em uma conta não existente
- [x] Não deve ser possível fazer saque quando o saldo for insuficiente
- [x] Não deve ser possível excluir uma conta não existente


## Testando método POST no Insomnia
![conta-bancaria-post](https://user-images.githubusercontent.com/82469705/171203267-19fb92cb-4c03-4cc9-8ef9-3d7f4882bb16.PNG)

### Valindando CPF existente
![conta-bancaria-post-usuario-existente](https://user-images.githubusercontent.com/82469705/171203790-d3c7cbfe-4f48-4c9f-a1ea-e364f0fab773.PNG)

### Criando deposito na conta
![conta-bancaria-post-depoisto](https://user-images.githubusercontent.com/82469705/171235635-85454fb3-c030-44ac-b776-510a2abff4bc.PNG)

### Métodos HTTP
![conta-bancaria-metodos](https://user-images.githubusercontent.com/82469705/171264841-e9966945-4a77-4f5e-94e8-82d3c2cb1040.PNG)

