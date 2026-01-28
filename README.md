# Controle de Despesas

Este é um aplicativo simples de controle de despesas que permite aos usuários adicionar, visualizar e excluir transações financeiras, mantendo um registro de seu saldo, receitas e despesas. Os dados são persistidos no armazenamento local do navegador.

## Funcionalidades

*   **Adicionar Transação:** Insira o nome e o valor da transação (valores positivos para receitas, negativos para despesas).
*   **Visualizar Resumo:** Acompanhe o saldo atual, o total de receitas e o total de despesas.
*   **Listar Transações:** Veja uma lista de todas as transações adicionadas.
*   **Excluir Transação:** Remova transações da lista.
*   **Persistência de Dados:** As transações são salvas localmente no navegador, garantindo que os dados não sejam perdidos ao recarregar a página.
*   **Salvar Dados:** Exporte todas as transações para um arquivo CSV para backup ou controle externo.

## Tecnologias Utilizadas

*   **HTML5:** Para a estrutura e conteúdo da aplicação.
*   **CSS3:** Para a estilização e aparência moderna da interface do usuário.
*   **JavaScript (ES6+):** Para a lógica da aplicação e manipulação do DOM.

## Como Executar o Projeto

1.  **Clone o repositório** (se estiver em um sistema de controle de versão) ou baixe os arquivos do projeto.
2.  Abra o arquivo `index.html` em seu navegador web preferido.

Não é necessário nenhum servidor web para executar este aplicativo, pois ele funciona inteiramente no lado do cliente.

## Estrutura do Código

*   `index.html`: Contém a estrutura HTML principal da aplicação, incluindo os elementos para exibição do saldo, listas de transações e o formulário para adicionar novas transações.
*   `style.css`: Define todos os estilos CSS que dão à aplicação sua aparência moderna, cores e layout responsivo.
*   `script.js`: Contém toda a lógica JavaScript, incluindo:
    *   Seleção de elementos do DOM.
    *   Manipulação de transações (adicionar, remover).
    *   Cálculo e atualização do saldo, receitas e despesas.
    *   Renderização da lista de transações.
    *   Integração com o Local Storage para persistência de dados.

## Uso

1.  Ao abrir o `index.html`, você verá o saldo atual, receitas e despesas.
2.  Use o formulário "Adicionar transação" para inserir novas transações:
    *   No campo "Nome", digite uma descrição para a transação.
    *   No campo "Valor", insira um número. Use um sinal de `+` ou nenhum sinal para receitas (ex: `100.00`) e um sinal de `-` para despesas (ex: `-50.00`).
3.  Clique no botão "Adicionar" para registrar a transação.
4.  A lista de transações será atualizada, e o resumo de saldo, receitas e despesas será recalculado automaticamente.
5.  Para excluir uma transação, passe o mouse sobre ela na lista e clique no botão `x` vermelho que aparece.
6.  Para salvar suas transações em um arquivo CSV no seu computador, clique no botão "Salvar Dados" localizado acima do formulário de adicionar transação.

## Modernização

A aparência do aplicativo foi recentemente atualizada para um design mais moderno, com uma paleta de cores aprimorada, tipografia mais limpa, sombras sutis e elementos interativos aprimorados, proporcionando uma experiência de usuário mais agradável.
