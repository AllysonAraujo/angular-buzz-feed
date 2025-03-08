# Clone do BuzzFeed Quiz com Angular

Este repositório contém um projeto de **clone do BuzzFeed** focado em **quizzes interativos**, utilizando o **Angular** como principal tecnologia.

## Tecnologias Utilizadas

- **Angular**: Framework JavaScript para a construção de aplicações web de uma única página.
- **HTML**: Estruturação do conteúdo da página.
- **CSS**: Estilização e layout da página.
- **TypeScript**: Linguagem utilizada para escrever o código do Angular.

## Funcionalidades

Este clone foca em quizzes interativos, permitindo aos usuários:

- Escolher entre diferentes opções de respostas.
- Ver uma pontuação ou resultado ao final do quiz com base nas respostas fornecidas.
- Navegar entre perguntas de forma dinâmica.
- A visualização e estilo são baseados em quizzes típicos encontrados no BuzzFeed.

### Como Funciona:

1. O usuário escolhe uma resposta para cada pergunta.
2. Ao final do quiz, o sistema calcula e exibe uma resposta personalizada ou pontuação final com base nas escolhas feitas.
3. Cada quiz pode ter várias perguntas com diferentes tipos de respostas.

## Como rodar o projeto

### Requisitos

- **Node.js**: Certifique-se de ter o Node.js instalado. Você pode verificar isso rodando o seguinte comando no terminal:
  ```bash
  node -v
  ```
- **Angular CLI**: Se não tiver o Angular CLI instalado, você pode instalá-lo globalmente utilizando o npm:
  ```bash
  npm install -g @angular/cli
  ```
## Passos para rodar o projeto

1 - Clone este repositório para sua máquina local:

```bash
git clone https://github.com/AllysonAraujo/angular-buzz-feed/
```
2 - Navegue até o diretório do projeto:
```bash
cd projeto-buzzfeed
```
3 - Instale as dependências do projeto:
```bash
npm install
```
4 - Inicie o servidor de desenvolvimento:
```bash
ng serve
```
5 - Abra o navegador e acesse http://localhost:4200 para ver o projeto em execução.

## Estrutura do Projeto
Componentes: Os componentes principais incluem o componente para perguntas, respostas, e a página de resultados.  

Serviços: Um serviço para controlar a lógica do quiz, como contar as respostas e calcular os resultados.  

Roteamento: A navegação entre as páginas do quiz é feita via roteamento Angular.



