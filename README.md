# API-RPA-TOOLKIT

A API-RPA-TOOLKIT é uma poderosa API Python baseada em FastAPI que oferece um conjunto abrangente de ferramentas para automação de processos robóticos (RPA). Com rotas flexíveis que suportam a recepção e envio de dados nos formatos base64, string e JSON, essa API possibilita a automação eficiente e escalável de uma variedade de tarefas, aprimorando a produtividade e otimizando fluxos de trabalho. Ela foi projetada para integração perfeita com o Power Apps, permitindo a rápida importação e utilização em aplicativos como o Power Automate e o Power BI.

## Rotas Disponíveis

A API-RPA-TOOLKIT fornece as seguintes rotas:

- **convert-document**
  - `/to-text`: Converte o documento para texto
  - `/to-json`: Converte o documento para JSON
  - `/to-image`: Converte o documento para imagem
  - `/to-pdf`: Converte o documento para PDF

- **process-text**
  - `/clean`: Limpa o texto
  - `/enhance`: Melhora a qualidade do texto
  - `/format`: Formata o texto

- **process-json**
  - `/filter`: Filtra o JSON
  - `/grouper`: Agrupa o JSON

- **process-pdf**
  - `/stamp`: Carimba o PDF

- **generate**
  - `/datetime`: Gera data e hora
  - `/period`: Gera período

- **identify**
  - `/document-type`: Identifica o tipo de documento
  - `/document-category`: Identifica a categoria do documento
  - `/document-issuer`: Identifica o emissor do documento

- **extract-fields**
  - `/invoice`: Extrai campos específicos de uma fatura

- **repair**
  - `/date`: Repara a data

## Como Usar

Para utilizar a API-RPA-TOOLKIT, siga as instruções abaixo:

1. Clone este repositório em sua máquina local.
2. Instale as dependências necessárias usando o [Poetry](https://python-poetry.org/): `poetry install`.
3. Inicie o servidor local com o [Uvicorn](https://www.uvicorn.org/): `poetry run uvicorn main:app --reload`.
4. Acesse a API através da URL: `http://localhost:8000`.

## Documentação

A documentação completa da API-RPA-TOOLKIT está disponível em [Swagger UI](http://localhost:8000/docs) durante a execução do servidor local.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma *issue* ou enviar um *pull request* com melhorias, correções ou novas funcionalidades.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
