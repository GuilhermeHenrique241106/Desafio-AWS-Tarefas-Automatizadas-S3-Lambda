Desafio de Projeto: Executando Tarefas Automatizadas com Lambda Function e S3

O que eu aprendi neste laboratório:
- O conceito de Arquitetura Orientada a Eventos, onde uma ação (como um upload) dispara um processo automático.
- Como o Amazon S3 atua como um repositório de arquivos seguro e escalável na nuvem.
- O funcionamento do AWS Lambda para executar códigos (funções em Python) no modelo Serverless, sem a necessidade de gerenciar servidores.
- Como integrar serviços de computação com bancos de dados NoSQL (Amazon DynamoDB) para persistência rápida de dados.
- O papel do Amazon API Gateway e de Webhooks para permitir que clientes externos façam consultas seguras ao sistema.

Passo a passo executado:
- Desenhei e mapeei o fluxo completo da infraestrutura utilizando a ferramenta Draw.io.
- Simulei o envio (upload) de um arquivo JSON de Nota Fiscal para o bucket do Amazon S3.
- Configurei e ativei o endpoint do Webhook para receber as notificações do ecossistema.
- Testei a requisição de consulta da API utilizando o ID da nota fiscal ("NF-10"), validando o recebimento dos dados estruturados com sucesso (Status 200 OK).
- Documentei toda a experiência técnica, os insights adquiridos e as evidências de teste em um repositório estruturado no GitHub.
