<h1 align="center">
 # Descentragram
</h1>
<p align="center">
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-layout">Layout</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-como-executar">Como executar</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-licença">Licença</a>
</p>

<p align="center">
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=8257E5&labelColor=000000">
</p>

<br>

## ✨ Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [React](https://reactjs.org)

## 💻 Projeto

Decentragram e um app que atravez de um smart contract de upload de fotos onde assinamos a transação via MetaMask 
e a imagem e enviada a carteira e exibida na tela.

## 🚀 Como executar

- Clone o repositório
- Instale as dependências com `npm install`
- Abra o terminal e inicie o servidor do seu editor [`VScode`](https://code.visualstudio.com/) com `npm run start`

Agora você pode acessar [`localhost:3000`](http://localhost:3000) do seu navegador.

Abra seu [`Ganache`](https://trufflesuite.com/ganache/) e conecte-se a [`MetaMask`](https://metamask.io/download/)
atravez do RPC Server 

<p align="center">
  <img alt="RPC" src="./public/img/ganache.png">
</p>

<p>
  Abra sua MetaMask e escolha o servidor, entre em Add Network
</p>

<p align="center">
  <img alt="RPC" src="./public/img/addNetWork.png">
</p>

## Dicas

- Adicione RCP URL da ganache e o chain ID
- Copie 2 chaves privadas do ganache e adicione em importar conta no MetaMask
- Abra o terminal e vicule o contrato a pagina usando o comando `truffle migrate --reset`

<p align="center">
  <img alt="RPC" src="./public/img/migrateABI.png">
</p>

O home deve ficar assim

<p align="center">
  <img alt="RPC" src="./public/img/home.png">
</p>

Agora já podemos "importar" imagens para a nossa carteira, após escolher o arquivo, assine a transação :

<p align="center">
  <img alt="RPC" src="./public/img/transacao.png">
</p>

Atualize a página 😄

<p align="center">
  <img alt="RPC" src="./public/img/fim.png">
</p>

## 📄 Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.

---
# Lembrando que o conteúdo desse repositorio e apenas para apredizagem 



