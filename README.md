# Arquitetura de Software

![Badge](https://img.shields.io/static/v1?label=SOLID&message=SOLID&color=important&style=for-the-badge) ![Badge](https://img.shields.io/static/v1?label=API_REST&message=API_REST&color=f00&style=for-the-badge) ![node-lts](https://img.shields.io/node/v-lts/lts?logo=node.js&style=for-the-badge) ![npm type definitions](https://img.shields.io/npm/types/typescript?logo=typescript&logoColor=blue&style=for-the-badge)

## Princípios do SOLID

SOLID é um conjunto de cinco princípios, onde cada letra do acrônimo corresponde a um princípio.

São eles:

Letra | Sigla | Nome | Tradução | Definição
----- | ----- | ---- | -------- | ---------
S | **SRP** | Single-Responsability Principle | Princípio da Responsabilidade Única | Uma classe deve ter uma, e somente uma responsabilidade.
O | **OCP** | Open-Closed Principle | Princípio Aberto-Fechado | Uma classe deve ser aberta para extensões, mas fechada para modificações.
L | **LSP** | Liskov Substitution Principle | Princípio da Substituição de Liskov | As classes bases podem ser substituíveis por suas classes derivadas.
I | **ISP** | Interface Segregation Principle | Princípio da Segregação da Interface | Muitas interfaces específicas são melhores que uma interface única. 
D | **DIP** | Dependency Inversion Principle | Princípio da Inversão da Dependência | As classes devem depender, sempre, de uma abstração e não de uma implementação.

Os princípios SOLID, quando bem aplicados, trazem como benefícios:

  - A fácil realização de manutenção, adaptação e ajuste às alterações de escopo;
  - Proporciona uma melhor experiência em testes e fácil entendimento do código;
  - Flexibilidade para alterações com menor esforço necessário;
  - Fornece o máximo de reaproveitamento;
  - Permite que um software permaneça o máximo de tempo possível em utilização.

Os princípios SOLID, quando bem aplicados, evitam problemas comuns, tais como:

  - Difuculdade na realização de testes e/ou criação de testes de unidade;
  - Código macarrônico, sem estrutura ou padrão;
  - Dificuldades em isolar funcionalidades do software;
  - Duplicação de código em diversos pontos do sistema;
  - Fragilidade, o código quebra facilmente em vários pontos após alguma alteração.