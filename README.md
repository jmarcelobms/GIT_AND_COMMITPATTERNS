<h1>PADRÃO DE COMMITS BMS</h1>

### Tipo

Um prefixo curto que representa o tipo de mudança, e pode ser:

`feat`: Nova funcionalidade <br />
`fix`: Correção de bug <br />
`perf`: Melhoria de performance <br />
`revert`: Reversão para um estador anterior <br />
`docs`: Documentação <br />
`style`: Alterações que não afetam o significado do código (espaço em branco, formatação, etc) <br />
`chore`: Tarefas diversas, sem alteração do código de produção (mudanças em configurações, etc) <br />
`refactor`: Alteração de código que não corrige um bug, nem adiciona um recurso <br />
`test`: Adição de testes ausentes ou correção de testes existentes <br />
`build`: Mudanças que afetam o sistema de build ou dependências externas <br />

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
