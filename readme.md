# Explique com suas paalvras o funcionamento do models, controller e fale sobre endopoints no projeto.

## Models
O projeto atualmente conta com 3 models dentro das pastas: aluno.js, curso.js, professor.js.
alunos.js: Realiza o create, para criar um aluno com nome, email e id do curso. Utiliza o update para atualizar nome e email do aluno. E o delete que realiza a exclusão do aluno na tabela.
curso.js: Realiza o create do curso, com o nome id. Update, atualizando também com nome e id. E o delete excluindo o curso do banco de dados.
professor.js: Adicione o professor com nome e email. Atualiza, o id, nome e email. Deleta o id do professor e ele no banco de dados.

## Controller
alunoController.js: o arquivo é responsável por entender as requisições relacionadas a alunos na aplicação web, feita com Node.js. Ele importa dois modelos Aluno e Curso, e exporta várias funções para manipular os dados.
cursoController.js: gerencia as ações relacionadas aos cursos na aplicação. Ele se comunica com o modelo Curso para criar, atualizar e deletar cursos no banco de dados.
professorController.js: Esse código define o controller de professores, ou seja, as funções responsáveis por lidar com as ações feitas em relação aos professores no sistema. Ele se comunica com o modelo Professor para buscar, criar, atualizar e deletar dados.

## Endpoints
http://localhost:3000/alunos: Endpoint para direcionar para as funções do aluno.
http://localhost:3000/professores: Endpoint para direcionar que realiza as alterações no professores.


Licença
-------

Este projeto está licenciado sob a Licença MIT.

Este README.md fornece uma visão geral clara do boilerplate, incluindo instruções de instalação, configuração do banco de dados, funcionalidades principais, scripts disponíveis, estrutura de diretórios, como contribuir e informações de licença. Certifique-se de personalizar as seções com detalhes específicos do seu projeto conforme necessário.
