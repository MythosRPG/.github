## Clean Code

Clean Code, ou código limpo, refere-se a um estilo de programação que enfatiza a legibilidade, simplicidade e manutenibilidade do código. A ideia central é escrever código que seja fácil de entender e manter, tanto para o desenvolvedor original quanto para outros membros da equipe. Seguir os princípios de Clean Code é fundamental para produzir software de alta qualidade.

### Princípios e Práticas de Clean Code

- **Nomes significativos:** Use nomes claros e descritivos para variáveis, funções, classes e outros elementos do código. Nomes bem escolhidos facilitam a compreensão do propósito e do comportamento do código.

- **Funções pequenas e coesas:** Escreva funções curtas que realizam uma única tarefa. Funções menores são mais fáceis de entender, testar e reutilizar.

- **Evite repetições:** Evite duplicar código. Em vez disso, extraia trechos duplicados para funções ou classes reutilizáveis. Isso reduz a redundância e facilita futuras alterações.

- **Comentários significativos:** Use comentários para explicar partes complexas do código, intenções, restrições ou limitações importantes. No entanto, o código deve ser autoexplicativo sempre que possível, evitando comentários óbvios ou redundantes.

- **Formatação consistente:** Siga um estilo de formatação consistente em todo o código, incluindo indentação, quebras de linha e organização geral. Uma formatação consistente facilita a leitura e a compreensão do código.

- **Testes unitários:** Escreva testes unitários para garantir que o código funcione conforme o esperado. Testes automatizados ajudam a identificar problemas precocemente e adicionam uma camada extra de documentação para o código.

- **Separação de responsabilidades:** Divida o código em partes com responsabilidades claras e distintas. Isso facilita a manutenção e permite que cada componente seja modificado ou substituído de forma independente.

- **Princípio do mínimo surpreendente:** Escreva o código de forma que seja intuitivo para quem o utiliza. Evite comportamentos inesperados. O código deve ser previsível e seguir convenções amplamente aceitas.

- **Refatoração contínua:** Melhore o código constantemente por meio de refatorações. Refatorar envolve reestruturar o código existente sem alterar seu comportamento externo, buscando melhorar sua legibilidade, simplicidade e eficiência.

- **Atenção à complexidade:** Evite criar código excessivamente complexo. Procure por soluções simples e diretas. A simplicidade ajuda a reduzir erros, facilita a manutenção e melhora a legibilidade.

### Ferramentas para Clean Code

Existem várias ferramentas que podem ajudar a garantir que o código siga os princípios de Clean Code. Aqui estão três delas: **Prettier**, **ESLint** e **EditorConfig**.

#### **Prettier:**
O Prettier é uma ferramenta de formatação de código que automatiza a aparência do código para manter um estilo consistente em todo o projeto. Com o Prettier, você não precisa se preocupar com a formatação manual, pois ele faz isso automaticamente. Ele suporta várias linguagens de programação e pode ser integrado aos editores de texto mais utilizados. Na VTEX, é comum utilizar a configuração **@vtex/prettier-config** para garantir que o código siga as diretrizes de estilo da empresa.

#### **ESLint:**
O ESLint é uma ferramenta de análise estática de código que verifica o código em busca de erros, padrões incorretos e possíveis problemas de segurança. Ele permite configurar regras personalizadas e aplicá-las ao código-fonte. No contexto da VTEX, o ESLint geralmente é configurado para estender um conjunto de regras chamado "vtex" e garantir conformidade com o Prettier por meio da regra "prettier/prettier".

#### **EditorConfig:**
O EditorConfig é um arquivo de configuração que ajuda a manter a consistência de estilo entre diferentes editores de texto e IDEs. Ele define configurações como indentação, estilo de quebra de linha e tamanho de indentação, que são compartilhadas entre os membros da equipe para garantir um estilo de codificação uniforme. O EditorConfig é suportado por vários editores e IDEs populares.

---

Seguindo esses princípios e utilizando essas ferramentas, você estará no caminho certo para escrever código limpo, legível e fácil de manter, contribuindo para um software de alta qualidade.
