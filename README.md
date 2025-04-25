# HardHat + Solidity – Projeto Base para Contratos Inteligentes
 
Este repositório é uma demonstração prática do uso do [HardHat](https://hardhat.org/), uma das ferramentas mais populares para o desenvolvimento, teste e implantação de contratos inteligentes escritos em [Solidity](https://soliditylang.org/).  
 
O objetivo é fornecer uma base sólida e personalizável para desenvolvedores que desejam criar, testar e evoluir contratos inteligentes em diversos cenários.
 
## 🚀 Sobre o Projeto
 
Este projeto foi inicializado com a estrutura básica do HardHat, contendo:
 
- Ambiente de desenvolvimento local
- Scripts de compilação, testes e deploy
- Exemplo simples de contrato inteligente
- Pronto para ser expandido com funcionalidades como:
  - Tokens (ERC-20, ERC-721, ERC-1155)
  - DAO
  - Voting systems
  - Wallets e Marketplaces
  - Integração com frontends Web3
 
## 🛠️ Tecnologias Utilizadas
 
- [HardHat](https://hardhat.org/)
- [Solidity](https://soliditylang.org/)
- [Node.js](https://nodejs.org/)
- [Chai](https://www.chaijs.com/) (para testes)
- [Ethers.js](https://docs.ethers.io/)
 
## 📂 Estrutura do Projeto
 
```plaintext
solidity-hardhat-base/
├── contracts/               # Contratos inteligentes em Solidity
│   └── ExampleContract.sol
├── scripts/                 # Scripts para deploy e interação
│   └── deploy.js
├── test/                    # Testes automatizados
│   └── ExampleContract.test.js
├── hardhat.config.js        # Configuração do HardHat
├── package.json             # Dependências do projeto
└── README.md                # Documentação
