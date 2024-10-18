

## DDD - Domain-Driven Design

**Domain-Driven Design (DDD)** é uma abordagem para desenvolver software que foca na compreensão e modelagem dos domínios de negócio, alinhando a solução técnica ao problema que o software pretende resolver. Isso significa que o desenvolvimento não é apenas sobre escrever código, mas sim sobre entender profundamente o que o negócio faz e como o software pode suportar isso.

### Introdução à Programação Orientada a Objetos (POO)

Para entender DDD, é importante ter uma boa base em **Programação Orientada a Objetos (POO)**, já que ela permite criar modelos que representam bem a realidade do domínio.

#### Princípios Básicos de Programação Orientada a Objetos:
- **Programação Estruturada vs. Programação Orientada a Objetos**:
  - Na programação estruturada, o código é organizado em blocos lógicos e funções.
  - Na POO, o foco está em objetos, que combinam dados e comportamento (funções), facilitando a modelagem de problemas complexos.

- **Classes e Objetos**: 
  - Uma **classe** é como uma "fábrica" para criar **objetos**. Ela define o que os objetos terão e farão (dados e comportamento).
  - Um **objeto** é uma instância dessa classe, ou seja, algo criado a partir da classe.

- **Encapsulamento**:
  - Significa esconder os detalhes internos de um objeto e expor apenas o necessário, tornando o código mais seguro e fácil de manter.

- **Herança**:
  - Permite que uma classe herde características (atributos e métodos) de outra classe, promovendo a reutilização de código.

- **Polimorfismo**:
  - Refere-se à capacidade de um objeto ser tratado de maneiras diferentes, dependendo do contexto. Por exemplo, várias classes podem compartilhar a mesma interface, mas cada uma implementa o comportamento de forma distinta.

- **Interfaces e Abstração**:
  - Uma **interface** define um contrato (quais métodos devem ser implementados), e a **abstração** é o processo de simplificar sistemas complexos, focando no que é essencial.

#### Exemplos práticos com Java
- Em DDD, você pode usar Java ou qualquer linguagem orientada a objetos para modelar conceitos do mundo real, criando classes que representem entidades do domínio, e aplicando as ideias de encapsulamento, herança, etc.

### Livros Recomendados
- **"Domain-Driven Design" de Eric Evans**: Livro fundador da abordagem DDD, explica em profundidade como modelar domínios complexos.
- **"Implementing Domain-Driven Design" de Vaughn Vernon**: Um guia mais prático para quem deseja implementar DDD no desenvolvimento de software.

---

## Conceitos Importantes em DDD

- **Domínio**: 
  - O domínio é o "universo" do problema que o software pretende resolver. Por exemplo, se você está desenvolvendo um sistema bancário, o domínio seria todo o contexto de operações bancárias.

- **Subdomínio**:
  - Dentro de um domínio, existem várias partes menores que representam áreas específicas. No exemplo do banco, um subdomínio pode ser "Empréstimos", outro pode ser "Contas Correntes".

- **Linguagem Ubíqua**:
  - É a linguagem comum que todos, tanto desenvolvedores quanto pessoas de negócio, usam para falar sobre o domínio. Essa linguagem ajuda a manter todos alinhados e a criar um modelo de software que realmente resolve os problemas certos.

- **Agregados**:
  - Um agregado é um grupo de objetos que pertencem juntos e são tratados como uma única unidade. Por exemplo, um **pedido** em um sistema de e-commerce pode ser um agregado, contendo itens, pagamento, e informações de entrega.

- **Entidade e Objeto de Valor**:
  - **Entidades**: São objetos que têm uma identidade única e contínua ao longo do tempo, como uma pessoa ou um produto.
  - **Objetos de Valor**: São objetos que não têm identidade própria, mas sim valor. Por exemplo, uma moeda de R$5,00 é um objeto de valor, pois seu valor é importante, mas a moeda em si não é única.

- **Eventos de Domínio**:
  - São mudanças importantes que ocorrem no domínio e que devem ser registradas. Por exemplo, no sistema bancário, um evento de domínio pode ser "cliente realizou um depósito", o que pode disparar ações no sistema.

