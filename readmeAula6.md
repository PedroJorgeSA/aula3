# Explique com suas palavras o papel de cada camada da arquitetura MVC usada neste projeto. Como o Model, o Controller e a View interagem entre si?
View: Através dos formulários na pagina inicial ele recebe os dados dos alunos e dos cursos
Controller: Passa as informações para o model por meio das requisições do view.
Model: Onde a regra de negocio do banco de dados foi criado e também onde é enviado as informações para criação das tabelas.

# Como ocorre o envio e o recebimento de dados no formato JSON neste projeto? Cite uma rota que responde em JSON e explique seu funcionamento.
O recebimento ocorre pelo controller qeu vai responder em formato JSON. Uma rota por exemplo: http://localhost:3000/alunos.

# Qual a importância de usar HTML básico com formulários e tabelas para organizar e manipular dados no navegador?
Usar HTML básico com formulários e tabelas é importante porque facilita a organização e a manipulação de dados diretamente no navegador, tornando a interface do sistema mais clara e fácil de usar.

# Por que esse tipo de estrutura ainda é útil em projetos back-end com Node.js?
Esse tipo de estrutura, usando HTML básico com formulários e tabelas, continua sendo útil em projetos back-end com Node.js porque facilita a integração entre o front-end e o back-end, permitindo que dados sejam organizados, exibidos e manipulados de forma simples e eficiente.