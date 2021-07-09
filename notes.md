# Fundamentos do NodeJS

## Métodos HTTP

- GET: Buscar uma informação dentro do servidor.
- POST: Inserir uma informação no servidor.
- PUT: Alterar uma informação no servidor.
- PATCH: Alterar uma informação específica no servidor.
- DELETE: Deletar uma informação no servidor.

## Tipos de parâmetros

- Route Params: usar para identificar um recurso para editar, deletar ou buscar.

  - É obrigatório.

  Exemplo: `/endpoint/:param`

- Query Params: usar para paginação, filtro.

  - Pode ser opcional.

  Exemplo: `/posts?page=4&orderBy=name`

- Body Pams: usar para inserção ou alteração de recursos.

  Exemplo:

  ```json
  {
    "name": "Ignite NodeJS"
  }
  ```
