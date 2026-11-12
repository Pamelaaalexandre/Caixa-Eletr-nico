# 🏦 GEN-CAIXA: Sistema de Caixa Eletrônico em Python

Este é um projeto simples e funcional de um simulador de **Caixa Eletrônico (ATM)** desenvolvido em Python. O sistema permite que o usuário gerencie seu saldo, realizando consultas, depósitos e saques de maneira interativa no console.

Este projeto foi desenvolvido como um exercício prático para consolidação de conceitos essenciais de lógica de programação e funções em Python.

---

## 🚀 Funcionalidades

- **💰 Consultar Saldo:** Exibe o saldo atual formatado de maneira clara.
- **💵 Depositar:** Permite somar novos valores ao saldo existente.
- **💸 Sacar:** Permite retirar valores do saldo atual, contando com uma validação para impedir que o usuário saque mais do que possui (saldo insuficiente).
- **🚪 Sair:** Opção para encerrar o atendimento de forma amigável.

---

## 🛠️ Tecnologias Utilizadas

- **Python 3** (Lógica de programação, condicionais, funções e entrada/saída de dados)

---

## 📁 Estrutura do Código

O projeto está estruturado em funções reutilizáveis para garantir a organização e boas práticas de desenvolvimento:

* `depositar(saldo)`: Recebe o saldo atual, solicita o valor do depósito e retorna o saldo atualizado.
* `sacar(saldo)`: Recebe o saldo atual, valida se há saldo suficiente, realiza o saque e retorna o saldo atualizado.
* **Menu Interativo**: Loop ou fluxo condicional que gerencia a escolha do usuário.

---

## 💻 Como Executar o Projeto

### Pré-requisitos
Você precisará ter o **Python 3** instalado em sua máquina.

### Passo a Passo

1. Clone este repositório para a sua máquina local:
   ```bash
   git clone https://github.com/seu-usuario/gen-caixa.git
