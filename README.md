# Gerenciador de Tarefas com LocalStorage

Este é um **gerenciador de tarefas** simples, desenvolvido para permitir que os usuários adicionem, editem, removam e marquem tarefas como concluídas. O projeto utiliza **localStorage** para armazenar as tarefas no navegador, o que garante que os dados sejam mantidos entre sessões, mesmo após o fechamento ou recarregamento da página.

## Objetivo

O principal objetivo deste projeto é criar um gerenciador de tarefas funcional, onde as informações sejam armazenadas **localmente** no navegador utilizando **localStorage**. Isso permite que o usuário tenha acesso às suas tarefas mesmo após o fechamento da aba ou do navegador, sem a necessidade de backend ou banco de dados.

Este projeto é ideal para quem deseja aprender como utilizar o **localStorage** para persistir dados no navegador e construir uma aplicação simples de gerenciamento de tarefas.

## Funcionalidades

- **Adicionar Tarefas**: O usuário pode adicionar novas tarefas à lista de forma simples e rápida.
- **Remover Tarefas**: Tarefas podem ser removidas da lista quando não forem mais necessárias.
- **Marcar Tarefas como Concluídas**: O usuário pode marcar tarefas como concluídas, ajudando a manter o controle sobre o que já foi feito.
- **Persistência de Dados**: As tarefas são armazenadas no **localStorage**, garantindo que elas fiquem disponíveis entre sessões, mesmo após o fechamento ou recarregamento da página.
- **Interface para Desktop**: A interface foi desenvolvida exclusivamente para visualização em telas de desktop, sem ajustes ou otimizações para dispositivos móveis.

## Tecnologias Utilizadas

- **HTML5**: Estrutura da página e conteúdo.
- **CSS3**: Estilização e layout da página.
- **JavaScript**: Lógica para adicionar, editar, remover e concluir tarefas.
- **localStorage**: Usado para persistir as tarefas localmente no navegador, garantindo que as informações sejam preservadas entre sessões.
- **Flexbox**: Para garantir que os elementos na página sejam bem posicionados e alinhados de maneira eficiente, especialmente em telas maiores.

## Como Rodar o Projeto

1. Clone o repositório:
    ```bash
    git clone https://github.com/guilerm3/TODO-LIST.git
    ```

2. Navegue até o diretório do projeto:
    ```bash
    cd TODO-LIST
    ```

3. Abra o arquivo `index.html` em um navegador de sua preferência.

4. O gerenciador de tarefas funcionará imediatamente, permitindo que o usuário interaja com a lista de tarefas e as altere, com os dados sendo armazenados no **localStorage**.

## Como Personalizar

1. **Funcionalidade**: Você pode adicionar novos recursos, como a possibilidade de categorizar as tarefas ou adicionar prazos.
2. **Estilos**: Modifique o arquivo `style.css` para ajustar as cores, fontes e layout da página conforme necessário.
3. **Armazenamento**: O projeto utiliza **localStorage** para persistir as tarefas. Caso queira integrar com um banco de dados, você pode explorar opções como **Firebase**, **MongoDB**, ou outro banco de dados NoSQL para armazenamento remoto de dados.
4. **JavaScript**: Sinta-se à vontade para adicionar novos comportamentos ou funcionalidades no arquivo `script.js`, como filtros de tarefas (ex: mostrar apenas tarefas concluídas ou pendentes).

## Desafios e Aprendizados

Durante o desenvolvimento deste projeto, explorei os seguintes conceitos:

- **localStorage**: Como utilizar **localStorage** para persistir dados no navegador, permitindo que as tarefas sejam preservadas entre sessões.
- **JavaScript DOM**: Como manipular o DOM com JavaScript para adicionar, editar, remover e concluir tarefas de forma dinâmica.
- **Flexbox**: Como utilizar **Flexbox** para posicionar e alinhar os elementos da página de forma eficiente.

## Site disponibilizado

<a href="https://guilerm3.github.io/TODO-LIST/" target="_blank">Clique aqui!</a> 
