# Login Dapp 

Projeto feito para aprender a como implementar um login na rede oficial da ICP.


## 🛠️ Tecnologias Utilizadas

- **Motoko**: Canister desenvolvido com a linguagem nativa da ICP.
- **React**: Front-end dinâmico e interativo.
- **Sass**: Estilização do front-end.
- **ICP Identity**: Integração com o sistema de login oficial da ICP.

# 🚧 Como Executar Localmente

1. **Certifique-se de que está utilizando um ambiente compatível**:  
   - Para usuários de **Windows**, é necessário instalar o **Windows Subsystem for Linux (WSL)** e configurar uma distribuição Linux.  

2. Instale a biblioteca de autenticação: 
```bash
npm install --save @dfinity/auth-client

```

3. Iniciar o ICP
```bash
dfx start --background
```

4. Faça o deploy do projeto:
```bash
dfx deploy
```
