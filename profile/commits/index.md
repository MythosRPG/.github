## Padrão de Commits

O Padrão de Commits é uma convenção amplamente adotada pela comunidade de desenvolvimento de software para padronizar as mensagens de commit em sistemas de controle de versão, como o Git. Este padrão tem como objetivo manter o histórico de alterações claro e compreensível, permitindo uma colaboração mais eficiente entre os membros da equipe.

Uma implementação popular desse padrão é o **Conventional Commits**. Essa abordagem define regras específicas para a formatação das mensagens de commit, proporcionando um registro consistente e estruturado do trabalho realizado. O formato básico de uma mensagem de commit no **Conventional Commits** é:

```<tipo>[escopo opcional]: <descrição>```

### Tipos de Commits:

- **feat**: Introdução de uma nova funcionalidade.
- **fix**: Correção de bugs.
- **docs**: Atualizações de documentação.
- **style**: Mudanças de formatação ou estilo que não afetam o código (ex.: espaçamento, indentação).
- **refactor**: Alterações de código que não corrigem bugs nem adicionam funcionalidades novas.
- **test**: Inclusão ou modificação de testes.
- **chore**: Tarefas de manutenção, como mudanças em scripts ou configurações.

### Escopo Opcional:

O escopo, embora opcional, oferece contexto adicional sobre a alteração, identificando, por exemplo, o módulo ou componente específico impactado pela mudança.

### Descrição:

A descrição deve ser uma breve e clara explicação da alteração realizada no commit.

---

### Benefícios do Padrão de Commits

A adoção do **Conventional Commits** traz benefícios significativos para a colaboração em projetos, facilitando a leitura e compreensão do histórico de alterações. Além disso, ferramentas de automação podem aproveitar esse padrão para realizar ações específicas com base no tipo de commit, como gerar notas de lançamento automaticamente ou executar testes relevantes.

### Ferramentas de Suporte

- **Husky**: Uma ferramenta popular usada em projetos Git para automatizar a execução de scripts antes de eventos como commits ou push. No contexto dos commits convencionais, **Husky** é frequentemente utilizado para garantir que as mensagens de commit sigam o formato correto.
  
- **Commit lint**: Uma biblioteca usada em conjunto com **Husky** para validar as mensagens de commit conforme as regras do **Conventional Commits**. Ele verifica se o formato está correto, se o tipo de commit é válido e se o escopo está sendo usado adequadamente, ajudando a manter a consistência e conformidade das mensagens no projeto.
