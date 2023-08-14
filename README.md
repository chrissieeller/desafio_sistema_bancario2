# DESAFIO SISTEMA BANCÁRIO - 2 

- Separar as funções existentes de "saque", "depósito" e "extrato" em funções. 
- Criar duas novas funções:
    - criar usuário (cliente);
    - criar conta corrente.

## Separação em Funções

Cada função possui uma regra na passagem de argumentos.

1. Função saque: recebe argumentos apenas por nome (keyword only);
2. Função depósito: recebe os argumentos apenas por posição (positional only);
3. Função extrato: recebe argumentos por posição e nome (positional only e keyword only).

## Criação de Funções

1. Criar usuário:
    - armazenamento em lista;
    - composto por: nome, data de nascimento, cpf e endereço; 
    - o endereço é uma string com formato: logradouro, número - bairro - cidade/estado; 
    - CPF armazenado apenas em número;
    - cadastrado apenas um usuário por CPF

2. Criar conta corrente: 
    - armazenamento em lista; 
    - composta por: agência, número da conta e usuário; 
    - o número da conta é sequencial, iniciando em 1; 
    - o número da agência é fixo: "0001"; 
    - cada usuário pode possui mais de uma conta. 
