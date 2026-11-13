# AGENTS.md — Regras globais do projeto

## 1. Objetivo

Este repositório contém um sistema modular de análise e otimização de currículos com inteligência artificial e visualização tridimensional utilizando Three.js.

O projeto é desenvolvido por quatro integrantes independentes.

## 2. Propriedade dos módulos

| Módulo | Diretório autorizado |
|---|---|
| Landing Page | `frontend/landing/` |
| Interface do agente | `frontend/app/` |
| Simulação Three.js | `frontend/simulation/` |
| Agente de inteligência artificial | `backend/` |

Antes de iniciar qualquer tarefa, identifique o módulo sob sua responsabilidade.

## 3. Isolamento obrigatório

Você está autorizado a criar, modificar, renomear e excluir arquivos exclusivamente dentro do módulo sob sua responsabilidade.

É permitido consultar arquivos de outros módulos para compreender contratos e dependências.

É proibido modificar arquivos de outros módulos, mesmo que a alteração pareça necessária, benéfica ou conveniente.

Não realize refatorações globais.

Não reorganize a estrutura do repositório.

Não altere configurações compartilhadas sem autorização explícita.

## 4. Arquivos protegidos

Os seguintes caminhos são considerados protegidos:

- `/contracts/`
- `/docs/`
- `/.github/`
- `/AGENTS.md`
- `/README.md`
- `/.gitignore`
- Arquivos de configuração e dependências da raiz.

Esses arquivos não podem ser modificados durante tarefas específicas de um módulo.

## 5. Contratos de integração

Os contratos existentes em `/contracts/` são a fonte oficial da verdade para comunicação entre módulos.

Sua implementação deve respeitar integralmente esses contratos.

É proibido modificar um contrato unilateralmente para adaptar o projeto à sua implementação.

Caso identifique a necessidade de alteração de um contrato, registre uma proposta na documentação local do módulo e comunique o responsável pela integração.

## 6. Documentação

Toda documentação referente à implementação deve permanecer dentro do diretório `docs/` do módulo sob sua responsabilidade.

Atualize a documentação local sempre que necessário.

Não atualize a documentação de outros módulos.

Não atualize a documentação global automaticamente.

## 7. Dependências

Não instale ou altere dependências globais sem autorização.

Priorize dependências declaradas e isoladas no próprio módulo.

Registre novas dependências e suas justificativas na documentação local.

## 8. Desenvolvimento independente

Utilize mocks, fixtures e implementações simuladas para dependências externas ainda indisponíveis.

Não implemente funcionalidades pertencentes a outros módulos para desbloquear sua tarefa.

## 9. Verificação antes da entrega

Antes de concluir uma tarefa:

1. Verifique os arquivos modificados.
2. Confirme que todos pertencem ao módulo autorizado.
3. Execute os testes do módulo.
4. Verifique a compatibilidade com os contratos globais.
5. Atualize a documentação local.
6. Informe alterações, testes realizados e pendências.

## 10. Bloqueios

Caso uma tarefa exija alterações fora do módulo autorizado, interrompa somente a parte bloqueada, registre o problema e solicite autorização ao responsável.

Não tente contornar as restrições deste documento.

A integridade do projeto e a independência dos módulos têm prioridade sobre a conclusão isolada de uma tarefa.