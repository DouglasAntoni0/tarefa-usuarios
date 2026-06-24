# Tarefa Usuários - Coleção Postman

![Postman](https://img.shields.io/badge/Postman-API%20testing-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![API](https://img.shields.io/badge/API-validacao-0A66C2?style=for-the-badge)
![QA](https://img.shields.io/badge/QA-testes%20de%20servico-2E7D32?style=for-the-badge)
![Contrato](https://img.shields.io/badge/Contrato-payloads%20e%20status-7D64FF?style=for-the-badge)

Coleção Postman voltada à validação de operações de usuários em API, com foco em execução manual guiada, organização de requisições e compartilhamento reprodutível.

O valor deste repositório está em demonstrar uma prática essencial de QA: validar serviços diretamente, sem depender da interface. Testar API ajuda a encontrar falhas mais cedo, reduz ruído visual e permite conversar com o backend usando evidências objetivas.

[<img src="https://run.pstmn.io/button.svg" alt="Run In Postman" style="width: 128px; height: 32px;">](https://app.getpostman.com/run-collection/47863974-4518bfe5-a791-4ddf-a182-1362249ed2e8?action=collection%2Ffork&source=rip_markdown&collection-url=entityId%3D47863974-4518bfe5-a791-4ddf-a182-1362249ed2e8%26entityType%3Dcollection%26workspaceId%3Dadeb1afb-5e88-42ed-a352-3087644513dc)

## Objetivo do projeto

O objetivo é disponibilizar uma coleção Postman para apoiar testes de API relacionados a usuários.

A coleção pode ser usada para:

- executar requisições de forma organizada;
- validar status code;
- observar payloads de resposta;
- testar cenários manuais de API;
- compartilhar requisições com outras pessoas;
- apoiar documentação técnica de endpoints.

## O que este projeto demonstra

| Competência | Aplicação prática | Valor para QA |
| --- | --- | --- |
| API testing | Requisições organizadas para validar comportamento de serviço | Permite testar regras sem depender da UI |
| Postman | Coleção compartilhável e executável via botão oficial | Facilita reprodução por outras pessoas |
| Documentação | Contexto claro para quem abre o repositório | Evita que o link da coleção fique sem explicação |
| QA em camadas | Validação de serviço antes da interface | Melhora velocidade de diagnóstico |
| Análise de contrato | Observação de status, headers e payload | Apoia comunicação com backend |

## Como usar

1. Clique em `Run in Postman`.
2. Importe ou faça fork da coleção.
3. Configure variáveis de ambiente, se a API exigir.
4. Execute as requisições.
5. Valide status, payloads, mensagens e regras de negócio retornadas.

## Checklist de validação sugerido

Ao executar uma coleção de API, é importante observar:

- endpoint correto;
- método HTTP adequado;
- autenticação, quando houver;
- headers obrigatórios;
- payload enviado;
- status code retornado;
- tempo de resposta;
- mensagens de erro;
- consistência entre request e response;
- comportamento para dados inválidos.

## Critérios de qualidade para a coleção

Uma coleção de API útil para QA deve permitir que outra pessoa reproduza o cenário com baixo atrito. Isso significa que nomes de requisições precisam ser claros, variáveis devem ter propósito definido e os exemplos de payload devem representar regras reais do serviço.

Neste repositório, o botão `Run in Postman` facilita o acesso rápido à coleção. O próximo nível de maturidade seria versionar também o arquivo exportado da collection e um ambiente com variáveis, deixando o fluxo ainda mais auditável.

## Leitura de QA sobre Postman

Postman é uma ferramenta muito útil para exploração, documentação e validação manual de APIs. Mesmo quando existe automação, coleções organizadas ajudam em momentos como:

- investigação rápida de bug;
- validação antes de automatizar;
- reprodução de cenário reportado;
- onboarding de pessoas no projeto;
- comunicação com desenvolvimento;
- documentação viva de endpoints.

## Resultado técnico

Este repositório evidencia uma prática essencial em QA: testar APIs de forma direta, organizada e reprodutível. Coleções Postman bem estruturadas aceleram investigação, documentação de contrato e comunicação com times de backend.

## Competências evidenciadas

- Testes manuais de API.
- Uso de Postman.
- Organização de coleção executável.
- Validação de status e payload.
- Pensamento em camadas de teste.
- Comunicação técnica por evidência.

## Possíveis evoluções

- Exportar a coleção para versionamento direto no repositório.
- Adicionar ambiente Postman com variáveis.
- Criar scripts de teste dentro das requisições.
- Incluir exemplos de payloads válidos e inválidos.
- Automatizar execução via Newman em CI/CD.

## Conclusão

Este repositório mostra uma habilidade prática e muito usada em QA: validar serviços diretamente. Uma boa coleção Postman reduz atrito, acelera diagnóstico e cria uma ponte clara entre requisito, API e evidência.
