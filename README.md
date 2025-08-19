# 🏦 Sistema Bancário em Python - Versão 2

Este projeto faz parte de um desafio de prática em Python.  
A ideia é evoluir um **sistema bancário simples** para uma versão mais **modularizada e organizada**, incluindo novos recursos.

---

## 🚀 Funcionalidades

- Criar **usuário** (cliente do banco) com CPF, nome, data de nascimento e endereço.
- Criar **conta corrente** vinculada a um usuário (agência padrão `0001`).
- Realizar **depósitos**.
- Realizar **saques** (até R$ 500,00 por operação e no máximo 3 saques diários).
- Consultar **extrato** com histórico de operações.
- **Listar contas correntes** existentes no sistema.

---

## 🛠 Estrutura do Código

- `depositar(valor)`: adiciona saldo e registra no extrato.
- `sacar(valor)`: efetua saque com regras de limite e saldo.
- `mostrar_extrato()`: exibe histórico de operações e saldo atual.
- `criar_usuario()`: cadastra um novo cliente.
- `criar_conta_corrente()`: cria uma conta associada a um usuário.
- `listar_contas()`: mostra todas as contas e seus titulares.

---

## 📂 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/sistema-bancario.git
