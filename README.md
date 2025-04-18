
# 🪙 Geração de Carteiras Bitcoin Testnet com Node.js

Este projeto tem como objetivo a geração de carteiras Bitcoin utilizando a rede de testes (testnet) com o auxílio de bibliotecas como `bip32`, `bip39` e `bitcoinjs-lib`. Ele foi criado como parte do curso da DIO para aprender como gerenciar carteiras HD (Hierarchical Deterministic) de forma programática.

---

## 🎯 Objetivo

O principal objetivo deste projeto é gerar uma carteira Bitcoin **testnet** e fornecer as seguintes informações:

- **Frase mnemônica (seed words)**
- **Seed derivada**
- **Chave privada no formato WIF**
- **Endereço da carteira no formato P2PKH**, compatível com faucets de testnet

---

## 🧰 Tecnologias Utilizadas

- **Node.js**: Ambiente de execução para JavaScript no servidor.
- **[bip32](https://github.com/bitcoinjs/bip32)**: Biblioteca para derivação de chaves hierárquicas.
- **[bip39](https://github.com/bitcoinjs/bip39)**: Biblioteca para gerar e converter frases mnemônicas.
- **[bitcoinjs-lib](https://github.com/bitcoinjs/bitcoinjs-lib)**: Biblioteca para criar transações e manipular endereços Bitcoin.

---

## 🚀 Como Executar

### 1. Clone o repositório:

```bash
  git clone https://github.com/AllianceTechSolutions/btc-testnet-wallet.git
    cd btc-testnet-wallet
```

### 2. Instale as dependências:

```
npm install bip32 bip39 bitcoinjs-lib
```

### 3. Execute o script:
```
node index.js
```
Isso irá gerar uma nova carteira Bitcoin testnet e mostrar as informações no terminal.

### 📌 Exemplo de Saída
Ao executar o script, você verá a seguinte saída no terminal (valores fictícios):

#### Carteira gerada

Endereço: moYiwQgNGYQfbkJ9HMbBR4gjc8Win1ubTG

Chave privada: cV7N6kZ.....
Seed: angle wire brand nuclear adjust ...

Endereço: Endereço Bitcoin Testnet gerado.

Chave Privada: A chave privada no formato WIF.

Seed: A frase mnemônica de 12 palavras gerada para a carteira.

### 🔗 Testando a Carteira
Você pode testar o endereço gerado nas seguintes plataformas:

Visualizar a carteira na Mempool Testnet:
[Mempool Testnet Explorer](https://mempool.space/testnet)

Solicitar Bitcoins Testnet (Faucet):
[Bitcoin Testnet Faucet](https://testnet-faucet.mempool.co/)

### 📁 Estrutura do Projeto

```
    btc-testnet-wallet/
    ├── index.js         # Script principal para gerar a carteira
    ├── package.json     # Dependências do projeto
    └── README.md        # Documentação do projeto
```

### 🧠 Aprendizado
Este projeto foi desenvolvido para reforçar o aprendizado sobre a criação de carteiras Bitcoin utilizando técnicas de Derivação Hierárquica Determinística (HD) e como interagir com a rede Testnet. Aprendi a utilizar as bibliotecas bip32, bip39 e bitcoinjs-lib para a geração de carteiras de forma programática.

### 👨‍💻 Desenvolvido por

***Thiago Arantes Borges Candido***

LinkedIn: [https://www.linkedin.com/in/thiago-borges-627659223/](https://www.linkedin.com/in/thiago-borges-627659223/)

WhatsApp: (31) 98477-6728

GitHub: [AllianceTechSolutions](https://github.com/AllianceTechSolutions)


