🪐 SWAPI Postman Testing
📝 Sobre o Projeto
Este repositório contém uma coleção do Postman focada em testes automatizados de API. O projeto foi desenvolvido para explorar a SWAPI (Star Wars API) exclusivamente através de requisições GET, consolidando conceitos essenciais de Quality Assurance (QA) e validação de dados em retornos JSON.

🚀 Funcionalidades e Testes Implementados
O foco principal deste projeto foi a criação de requisições dinâmicas (utilizando Path Variables) e o desenvolvimento de scripts de testes automatizados abrangentes. As validações incluem:

Status Code: Garantia de que a API responde com status 200 OK.

Estrutura de Dados: Verificação da presença de propriedades obrigatórias no corpo da resposta (ex: name, title, episode_id).

Type Checking: Validação de tipos de dados para garantir que a API está retornando exatamente o esperado (ex: verificando se episode_id é um number e director é uma string).

Validação de Conteúdo: Testes para garantir que os campos obrigatórios não retornem vazios.

🛠️ Tecnologias Utilizadas
Postman: Plataforma para estruturação das requisições e execução da Collection.

JavaScript: Linguagem utilizada para escrever os scripts de testes na aba Tests do Postman.

SWAPI: API RESTful pública utilizada como base de testes.

(Dica: Aqui você pode adicionar as tags dos Skill Icons de Postman e JavaScript, mantendo o mesmo padrão visual caprichado do seu perfil principal!)

⚙️ Como executar este projeto
Clone este repositório em sua máquina local.

Abra o Postman e clique em Import.

Selecione o arquivo da Collection (formato .json) salvo neste repositório.

Abra as requisições importadas, insira um ID válido na aba de Path Variables e clique em Send.

Verifique a aba Test Results para visualizar as validações automatizadas passando.
