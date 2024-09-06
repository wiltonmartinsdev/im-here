## Gerenciador de Participantes de Eventos

Esta é uma aplicação mobile desenvolvida com React Native e Expo que permite adicionar e remover participantes de eventos como treinamentos, palestras ou workshops. O principal objetivo do projeto é praticar os fundamentos do React Native.


## 🎨 Stacks utilizadas

- **React Native** - Uma biblioteca de código aberto que permite o desenvolvimento de aplicativos móveis para iOS e Android usando JavaScript e React. Com React Native, é possível criar aplicações nativas com a mesma base de código.
- **Expo** - Um conjunto de ferramentas e serviços que simplifica o desenvolvimento de aplicativos React Native, permitindo a prototipagem rápida, testes em dispositivos físicos e fácil integração com diversas bibliotecas nativas.
- **TypeScript** - Um superconjunto do JavaScript que adiciona tipagem estática ao código, ajudando a detectar erros mais cedo e a melhorar a qualidade e a manutenção do código.


## 🛠️ Pré-requisitos

-   Node.js instalado na máquina - versão 20.17.0-LTS ou superior .
-   NPM (Node Package Manager) para instalar as dependências necessárias do projeto.


## 🛠️ Instalação

- Clone o repositório, com o comando abaixo, no seu terminal:
   - Utizando HTTPS `https://github.com/wiltonmartinsdev/im-here.git` ou
   - Utilizando SSH: `git@github.com:wiltonmartinsdev/im-here.git`.
- Acesse o diretório do projeto: `cd im-here`.
- Certifique-se de ter o Node.js e o NPM instalados em sua máquina e depois digite no terminal o comando abaixo para instalar todas as dependências necessárias do projeto.

      npm install
    
## 🚀 Execução da Aplicação

-   Após instalar todas as dependências necessárias do projeto, agora poderá executá-lo da seguinte maneira:
-   Digite no terminal o comando abaixo:

          npm run android ou ios

          Após esse comando podemos testar a aplicação.

## ✨ Funcionalidades

- Adicionar participantes a uma lista
- Exibir a lista de participantes adicionados
- Remover participantes com confirmação de exclusão


## 📊 Status do Projeto

-  A aplicação encontra-se finalizada, mas, podendo ser implementada novas funcionalidades no futuro.


## 📄 Licença

![GitHub License](https://img.shields.io/badge/license-MIT-green)


## 📚 Aprendizados

Durante o desenvolvimento deste projeto, aprendi e pratiquei diversos conceitos fundamentais de React Native e desenvolvimento mobile. Alguns dos principais aprendizados incluem:

- **Gerenciamento de Estado com Hooks:** Usei useState para controlar o estado da lista de participantes e o valor do campo de entrada, o que me permitiu adicionar e remover participantes de maneira eficiente.
- **Componentização:** Separei o código em componentes reutilizáveis, como o componente Participant, para melhorar a organização e a legibilidade do código.
- **Interações com o Usuário:** Aprendi a trabalhar com componentes interativos do React Native como TextInput, TouchableOpacity e Alert para criar uma interface amigável e responsiva.
- **Manipulação de Listas com FlatList:** A prática com FlatList me ensinou a renderizar listas grandes de forma otimizada, além de utilizar keyExtractor para garantir que cada item na lista tivesse uma chave única.
- **Confirmação de Ações Críticas:** Implementei uma lógica de confirmação ao excluir um participante usando o Alert, o que melhorou a usabilidade e evitou remoções acidentais.
- **Expo:** Utilizei o Expo para configurar rapidamente o ambiente de desenvolvimento e testar a aplicação em diferentes dispositivos sem precisar de uma configuração complexa e isso facilitou o fluxo de desenvolvimento.
- **Validação Simples:** Apliquei validações no formulário para garantir que nomes de participantes não fossem adicionados repetidamente ou em branco, o que fortaleceu a robustez da aplicação.

Esses aprendizados foram valiosos para consolidar meus conhecimentos em React Native e preparar o terreno para projetos mais complexos no futuro.
