# AngularProject

Explicação das arquivos e pastas criadas automaticamente:

*ARQUIVOS*

- .gitignore = Serve para armazenar arquivos não desejados para serem trackeados pelo git.

- angular.json = contém diversar configurações. Ex: configs de build, inicialização do projeto com server, de teste, etc.

- package-lock.json = Informações de versões e bibliotecas que foram instaladas.

- package.json = dependências do nosso projeto.

- tsconfig.app.json = configs do typescript específicas para o nosso projeto. 

- tsconfig.json = configurações globais que se aplicam e todo o projeto. 

- tsconfig.spec.json = configuraões que vão ser utilizadas durante execução de testes unitários.

*PASTAS e seus ARQUIVOS*

- public = imgs e assets estáticos do projeto.

- src = código-fonte do projeto.
-style.css = design do projeto.
-main.ts = entry point da aplicação.
-index.html = arquivo que será renderizado pelo navegador, para o usuário.

- app 
--app.component.hmtl
--app.component.css
--app.component.ts
--app.component.spec.ts 
(Todos fazem referência ao componente principal "app")

--app.config.ts = é responsável por passar configs de como deve renderizar os componentes.
--app.routes.js = As rotas das páginas virtuais serão armazenadas aqui.