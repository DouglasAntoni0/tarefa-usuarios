# Tarefa de usuários — estrutura de coleção Postman

Exercício de organização de requisições para operações de usuários. O arquivo [tarefa (usuarios).postman_collection.json](<tarefa (usuarios).postman_collection.json>) está exportado e versionado no formato Postman Collection v2.1.

## Estado atual

O export contém cinco itens: cadastrar, listar, buscar por ID, editar e excluir usuário. Todos estão com método `GET`, sem URL, body, autenticação ou scripts `pm.test`. É uma estrutura inicial de coleção; ainda não contém chamadas executáveis nem validações automatizadas de CRUD.

O repositório não identifica a API alvo ou o contrato dos endpoints. Esses dados precisam ser definidos antes de completar as requisições. Um link de compartilhamento de outra versão da coleção não demonstra equivalência com este JSON.

## Inspecionar no Postman

```bash
git clone https://github.com/DouglasAntoni0/tarefa-usuarios.git
cd tarefa-usuarios
```

No Postman, use **Import** e selecione o JSON. A importação permite visualizar e editar os cinco itens. Para executá-los será necessário completar sua configuração.

## O que falta implementar

1. Identificar a API e documentar seu contrato.
2. Configurar URL base, rotas e métodos de cada operação.
3. Definir payloads, headers e autenticação quando exigidos.
4. Extrair IDs das respostas para os fluxos dependentes.
5. Criar exemplos e verificações de status, resposta e regras de negócio.
6. Exportar a coleção completa e um environment sem segredos.

O projeto ainda não possui Newman, pipeline de testes ou relatório de execução.
