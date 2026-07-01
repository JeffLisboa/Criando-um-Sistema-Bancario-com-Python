# 🏦 Sistema Bancário em Python — V2

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python" alt="Python">
  <img src="https://img.shields.io/badge/Versão-V2-success?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Em%20Evolução-purple?style=for-the-badge">
</p>

---

# 🚀 Sobre o Projeto

A segunda versão do sistema bancário traz uma grande evolução na estrutura do código, aplicando conceitos mais avançados da linguagem Python e melhorando significativamente a organização do projeto.

Além das operações bancárias básicas, agora o sistema permite:

✅ Cadastro de usuários
✅ Criação de contas bancárias
✅ Listagem de contas
✅ Separação do código em funções
✅ Melhor organização e reutilização de código
✅ Uso de parâmetros posicionais e nomeados
✅ Estrutura mais próxima de sistemas reais

---

# ✨ Funcionalidades

## 💰 Operações Bancárias

✔️ Depósito
✔️ Saque
✔️ Extrato

---

## 👤 Gestão de Usuários

✔️ Cadastro de novos usuários
✔️ Validação de CPF único
✔️ Armazenamento de dados do cliente

---

## 🏦 Gestão de Contas

✔️ Criação de contas bancárias
✔️ Associação de conta ao usuário
✔️ Listagem de contas cadastradas

---

# 🧠 Conceitos Aplicados

Esta versão trabalha conceitos mais avançados de programação:

* Funções
* Modularização
* Estruturas de dados
* Listas e dicionários
* Validação de informações
* Parâmetros posicionais (`/`)
* Parâmetros nomeados (`*`)
* Reutilização de código
* Organização de sistemas

---

# 💻 Demonstração do Sistema

```text id="a72kd9"
================ MENU ================
[d] Depositar
[s] Sacar
[e] Extrato
[nc] Nova conta
[lc] Listar contas
[nu] Novo usuário
[q] Sair
=>
```

---

# 📸 Exemplos de Uso

## 👤 Cadastro de Usuário

```text id="d82kq1"
Informe o CPF (somente número): 12345678900
Informe o nome completo: João Silva
Informe a data de nascimento (dd-mm-aaaa): 01-01-2000
Informe o endereço: Rua A, 123 - Centro - MG

=== Usuário criado com sucesso! ===
```

---

## 🏦 Criação de Conta

```text id="w9z2pa"
Informe o CPF do usuário: 12345678900

=== Conta criada com sucesso! ===
```

---

## 📄 Extrato

```text id="m81fla"
================ EXTRATO ================

Depósito:    R$ 200.00
Saque:       R$ 50.00

Saldo:       R$ 150.00

==========================================
```

---

# ⚙️ Regras do Sistema

| Regra            | Descrição                |
| ---------------- | ------------------------ |
| Limite de saque  | R$ 500,00                |
| Máximo de saques | 3 saques                 |
| CPF              | Não pode duplicar        |
| Conta bancária   | Vinculada a um usuário   |
| Depósitos        | Apenas valores positivos |

---

# 📂 Estrutura do Projeto

```text id="z81sdf"
v2/
│
├── sistema_bancario_v2.py
└── README.md
```

---

# ▶️ Como Executar

## Clone o repositório

```bash id="g73la2"
git clone https://github.com/JeffLisboa/Criando-um-Sistema-Bancario-com-Python.git
```

---

## Acesse a pasta

```bash id="u8sld1"
cd Criando-um-Sistema-Bancario-com-Python
```

---

## Execute o projeto

```bash id="j29dla"
python sistema_bancario_v2.py
```

---

# 📈 Evolução da V1 para V2

| V1                         | V2                             |
| -------------------------- | ------------------------------ |
| Código procedural simples  | Código modularizado            |
| Apenas operações bancárias | Usuários e contas              |
| Sem reutilização de código | Uso de funções                 |
| Estrutura básica           | Estrutura organizada           |
| Menor escalabilidade       | Mais próximo de sistemas reais |

---

# 🎯 Objetivo do Projeto

Este projeto foi desenvolvido para aprofundar conhecimentos em Python e demonstrar evolução prática no desenvolvimento de sistemas.

A V2 representa um avanço importante na organização e arquitetura do código.

---

# 👨‍💻 Autor

Desenvolvido por **Jefferson Lisboa**

📌 Projeto focado em evolução contínua e aprendizado em desenvolvimento backend com Python.

---

# ⭐ Contribuição

Sinta-se à vontade para abrir issues, sugerir melhorias ou contribuir com novas funcionalidades.
