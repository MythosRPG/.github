## Fluxo de Pull Request

O Fluxo de Pull Request é uma abordagem eficaz para o desenvolvimento de software que utiliza pull requests para promover a colaboração e a revisão de código dentro de uma equipe. Esse fluxo é particularmente vantajoso em projetos que seguem um modelo de branch baseado, como o **GitFlow**.

### O que é o **GitFlow**?

O **GitFlow** é um modelo de fluxo de trabalho que organiza o desenvolvimento em duas branches principais: "**main**" e "**develop**". A branch "**main**" representa a versão estável e pronta para produção do software, enquanto a branch "**develop**" é onde ocorre o desenvolvimento contínuo e a integração de novos recursos.

### Passos para Utilizar o Fluxo de Pull Request com **GitFlow**

1. **Criação de uma Branch de Feature:**
   Ao iniciar um novo recurso ou funcionalidade, o desenvolvedor cria uma branch de feature a partir da branch "**develop**". Esta branch é usada para isolar o desenvolvimento da nova funcionalidade, garantindo que o código em desenvolvimento não interfira no código estável.

2. **Desenvolvimento e Commits:**
   Durante o desenvolvimento na branch de feature, o desenvolvedor realiza as modificações necessárias e faz commits regulares. Recomenda-se seguir o padrão **Conventional Commits** para manter um histórico claro e organizado.

3. **Abertura do Pull Request:**
   Quando o desenvolvimento na branch de feature estiver concluído, o desenvolvedor abre um Pull Request (PR) para solicitar a revisão e a incorporação das alterações na branch "**develop**". O PR deve incluir uma descrição clara das mudanças, documentações adicionais, testes e referências relevantes.

4. **Revisão e Discussão:**
   Os membros da equipe revisam o código, fornecem feedback e discutem melhorias diretamente no PR. Esse processo é essencial para garantir a qualidade do código e a conformidade com os padrões do projeto.

5. **Resolução de Problemas e Atualizações:**
   Com base no feedback, o desenvolvedor faz as correções necessárias, realiza novos commits e atualiza o PR. Esse ciclo continua até que o código seja aprovado pelos revisores.

6. **Integração e Mesclagem:**
   Após a aprovação do PR, as alterações são mescladas na branch "**develop**". A branch de feature pode ser excluída ou mantida conforme necessário para histórico.

7. **Implantação e Lançamento:**
   Periodicamente, uma branch de release é criada a partir da branch "**develop**" quando as funcionalidades estão prontas para produção. Essa branch passa por testes finais e ajustes antes de ser mesclada na branch "**main**", resultando em uma nova versão estável do software.

### Benefícios do Fluxo de Pull Request com **GitFlow**

O Fluxo de Pull Request, quando aplicado em conjunto com o **GitFlow**, facilita a colaboração entre os membros da equipe e assegura que o código seja revisado e aprovado antes de ser integrado nas branches principais. Isso contribui para manter a qualidade do código, a integridade do repositório e a eficiência no lançamento de novas versões do software.
