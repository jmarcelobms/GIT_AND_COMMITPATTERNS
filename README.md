### Tipo

Um prefixo curto que representa o tipo de mudança, e pode ser:

`feat`: Nova funcionalidade
`fix`: Correção de bug
`perf`: Melhoria de performance
`revert`: Reversão para um estador anterior
`docs`: Documentação
`style`: Alterações que não afetam o significado do código (espaço em branco, formatação, etc)
`chore`: Tarefas diversas, sem alteração do código de produção (mudanças em configurações, etc)
`refactor`: Alteração de código que não corrige um bug, nem adiciona um recurso
`test`: Adição de testes ausentes ou correção de testes existentes
`build`: Mudanças que afetam o sistema de build ou dependências externas

### Escopo

O escopo (opcional) fornece informações contextuais adicionais.

- É contido entre parênteses: `feat(login): implementado calculo de desconto`
- Caso o escopo possua mais de uma palavra, deve ser separado por underline: `feat(teste_teste): implementado cancelamento de nota fiscal`

### Descrição

Contém uma descrição sucinta da mudança.

- Use o tempo presente imperativo: "atualizado", não "atualizando" ou "atualização"
- Sem primeira letra maiúscula e sem ponto final

---

ℹ️ Exemplos de commits


docs(readme): atualizado pré-requisitos
fix(gerenciamento_nota): bloqueado inputs caso a nota seja de cancelamento


| ✅ Faça isso                                 | ❌ Não faça isso                              |
| -------------------------------------------- | ---------------------------------------------- |
| docs(adr): adicionar padrões de commit       | docs(ADR): adicionar padrões de confirmação    |
| feat(gerenciamento_nota): adicionar edição   | feat(gerenciamento-nota): adicionar edição     |
| perf(api_webmania): forma de consumir a api  | ci(docker): Forma de consumir a api            |
| fix: devolução de nota                       | fix: fix devolução de nota                     |
| feat(base_url): atualizado base url           | feat(produto): atualizando base url            |

## Consequences

Isso leva a mensagens mais legíveis que são fáceis de seguir ao examinar o histórico do projeto.

teste