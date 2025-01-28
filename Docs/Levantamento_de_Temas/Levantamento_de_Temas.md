## Resumo Geral dos Levantamento de Temas

O objetivo principal é definir um tema de pesquisa que explore a relação entre **arquiteturas de software**, **qualidade** e outros fatores como **migração de arquiteturas**, **persistência de dados** e **injeção de dependência**. As sugestões foram elaboradas para combinar elementos teóricos e práticos, permitindo uma análise comparativa e aprofundada.

### 1. Área Principal:

*   **Engenharia de Software:** O foco principal é a aplicação de princípios e práticas de engenharia de software para construir sistemas de alta qualidade e analisar processos de migração.
*   **Arquitetura de Software:** O tema central envolve diferentes estilos arquiteturais, padrões de projeto, processos de migração e como eles afetam a qualidade do software.

### 2. Temas Específicos e Perguntas de Pesquisa

#### **Tema 1:** Impacto da Arquitetura de Software na Evolução e Qualidade de Sistemas de Software

*   **Foco:** Co-mudanças em módulos arquitetônicos, diferentes visões da arquitetura e métricas de co-mudança.
*   **Perguntas de Pesquisa:**
    *   **RQ1:** Co-mudanças dispersas entre múltiplos módulos arquitetônicos são mais propensas a defeitos do que co-mudanças localizadas dentro de um módulo?
    *   **RQ2:** Diferentes *surrogates* para a visão de módulo exibem resultados diferentes na relação entre dispersão de co-mudanças e defeitos?
    *   **RQ3:** Uma métrica que diferencia co-mudanças entre módulos tem maior correlação com defeitos do que uma métrica que não considera a arquitetura?

#### **Tema 2:** Arquiteturas de Software, Persistência de Dados e Injeção de Dependência: Impactos na Qualidade de Sistemas de Software

*   **Foco:** Arquiteturas limpas/hexagonais, persistência de dados (SQL/NoSQL), injeção de dependência, padrões para microsserviços e refatoração de sistemas legados.
*   **Perguntas de Pesquisa:**
    1.  Como a adoção de arquiteturas limpas ou hexagonais e a aplicação da injeção de dependência afetam a separação de preocupações e a testabilidade em sistemas que interagem com bancos de dados?
    2.  De que maneira a escolha entre bancos de dados relacionais e não relacionais impacta a arquitetura de software, a escalabilidade e a manutenibilidade, considerando a necessidade de consistência e disponibilidade de dados?
    3.  Quais padrões de arquitetura são mais adequados para microsserviços que lidam com persistência de dados, e como esses padrões podem garantir a consistência e a integridade dos dados em um ambiente distribuído?
    4.  Como a injeção de dependência pode ser introduzida em sistemas legados para facilitar a refatoração da arquitetura e a evolução da base de código, e quais os desafios e benefícios desse processo?
    5. De que forma a escolha de serviços em nuvem (BaaS, DaaS) impactam a arquitetura, a persistência de dados e a qualidade de aplicações móveis?

#### **Tema 3: Análise de Migrações de Arquitetura Monolítica para Microsserviços ou Soluções Desacopladas**

*   **Foco:** Dificuldades, estratégias e impactos de migrações de arquiteturas monolíticas para microsserviços ou outras soluções desacopladas.
*   **Possibilidades de pesquisa:**
    *   **Estudo de caso comparativo:** Analisar diferentes relatos de migração de arquiteturas, identificando os desafios e soluções adotadas.
    *   **Análise de padrões de refatoração:** Investigar como padrões de refatoração, como o Strangler Fig, são aplicados na prática durante a migração.
    *  **Impacto nos custos e desempenho:** Avaliar o impacto das mudanças arquiteturais nos custos operacionais e no desempenho das aplicações.
    *   **Aspectos culturais e organizacionais:** Explorar como a migração para microsserviços afeta a cultura e os processos de desenvolvimento das equipes.
*  **Perguntas-chave:**
    1.  Quais são os principais desafios enfrentados por organizações ao migrar de arquiteturas monolíticas para microsserviços, e como eles são abordados na prática?
    2.  Como as decisões sobre decomposição de sistemas monolíticos em microsserviços são tomadas, e quais os critérios utilizados para definir os limites dos serviços?
    3.  De que forma a adoção de microsserviços impacta a agilidade e a eficiência das equipes de desenvolvimento, e quais os benefícios reais obtidos em comparação com a arquitetura monolítica?

##### Inspiração para Pesquisa
    
   Giuliana Bezerra, mestre em Ciência da Computação pela Universidade Federal do Rio Grande do Norte (UFRN), mantém um canal no YouTube focado em Java, que serve como fonte de inspiração para diversas pesquisas. Durante minhas pesquisas, encontrei exemplos relevantes que podem ser aprofundados em um Trabalho de Conclusão de Curso (TCC), abordando temas de forma simples, acessível, mas ainda com o rigor necessário.
   
   Um exemplo destacado é o vídeo [**Microservices Patterns na Prática - Strangler Fig**](https://www.youtube.com/watch?v=92JBsFHC2Lw), publicado em 29 de julho de 2024, que reflete a atualidade e relevância do tema. Além disso, o código fonte utilizado no vídeo está disponível no [**repositório oficial do GitHub**](https://github.com/giuliana-bezerra/stranglerfig), oferecendo uma base sólida para estudos e experimentações práticas.

   Para apoiar pesquisas sobre o tema *Strangler Fig*, foram encontrados dois artigos recentes que demonstram a possibilidade de investigações relacionadas:

1. Microservice Migration Using Strangler Fig Pattern: A Case Study on the Green Button System
- **Ano de Publicação:** 2020  
- **Autores:** Chia-Yu Li, Shang-Pin Ma (National Taiwan Ocean University), Tung-Wen Lu  
- **Fonte:** Artigo disponível no [ResearchGate](https://www.researchgate.net/publication/349568403_Microservice_Migration_Using_Strangler_Fig_Pattern_A_Case_Study_on_the_Green_Button_System).  

2. Microservice Migration Using Strangler Fig Pattern and Domain-Driven Design
- **Ano de Publicação:** 2022  
- **Autores:** Shang-Pin Ma, Chia-Yu Li, Wen-Tin Lee, Shin-Jie Lee  
- **Fonte:** Artigo disponível no [Airiti Library](https://www.airitilibrary.com/Article/Detail/10162364-202211-202207150001-202207150001-1285-1303).  
 
### 3. Artigos que Podem Auxiliar (com pequeno resumo)

**Artigo 1:** "Mapeamento Sistemático da Literatura e Revisão da Literatura"
*   **Resumo:** Este artigo estabelece a base para o estudo, focando no impacto da arquitetura de software na qualidade e evolução dos sistemas. Ele apresenta as questões de pesquisa iniciais, métricas de co-mudança e reconstrução de arquitetura.

**Artigo 2:** "Adesão da Arquitetura de Microsserviços nas Grandes Corporações para Desenvolvimento ou Migração de Aplicações"
*   **Resumo:** Aborda a adoção da arquitetura de microsserviços em grandes empresas, comparando-a com a arquitetura monolítica e destacando seus benefícios. Pode auxiliar na compreensão das vantagens de microsserviços em relação a arquiteturas monolíticas, principalmente no contexto de persistência de dados e padrões de arquitetura.

**Artigo 3:** "Aplicando Refatorações em uma Arquitetura de Software Monolítica para uma Solução Utilizando Microsserviços"
*   **Resumo:** Apresenta a refatoração de uma arquitetura monolítica para microsserviços, utilizando o padrão Strangler Fig e a decomposição do banco de dados. Essencial para entender a transição para microsserviços e como abordar a persistência de dados neste contexto. É **fundamental** para o Tema 3.

**Artigo 4:** "Comparison between Ports in Hexagonal Architecture and Interfaces in Clean Architecture: A Conceptual and Practical Analysis"
*  **Resumo:** Compara os conceitos de Ports na Arquitetura Hexagonal e Interfaces na Arquitetura Limpa, destacando como eles promovem o isolamento da lógica de negócios e auxiliam na separação de responsabilidades. É crucial para entender a base teórica de arquiteturas limpas e como elas se relacionam com a persistência de dados e injeção de dependência.

**Artigo 5:** "Arquitetura Orientada a Serviços e sua Integração com Software as a Service"
*   **Resumo:** Explora a Arquitetura Orientada a Serviços (SOA) e sua integração com o modelo Software as a Service (SaaS), demonstrando como os princípios da SOA são aplicados em SaaS. Útil para entender como os serviços podem ser integrados em ambientes de nuvem, que são relevantes para o tema de persistência de dados e serviços.

**Artigo 6:** "Get Your Hands Dirty on Clean Architecture"
*   **Resumo:** Apresenta uma abordagem prática para a construção de aplicações web utilizando a arquitetura limpa e hexagonal, com foco na manutenibilidade e no desacoplamento. Essencial para compreender os conceitos de arquitetura limpa, injeção de dependência e como eles se relacionam com a persistência de dados. **Relevante** para o Tema 2.

**Artigo 7:** "Desenvolvimento e Análise de Duas Arquiteturas de Software para a Operação de um Serviço em Nuvem..."
*   **Resumo:** Compara arquiteturas monolíticas e de microsserviços em um serviço de nuvem, avaliando o desempenho e a escalabilidade. Útil para entender o impacto da arquitetura na escalabilidade e como diferentes abordagens de persistência (SQL/NoSQL) se comportam em diferentes arquiteturas. **Importante** para os Temas 2 e 3.

**Artigo 8:** "Migração de arquitetura: Monolítico para Microsserviços usando Domain-Driven Design"
*   **Resumo:** Aborda a migração de uma arquitetura monolítica para microsserviços usando Domain-Driven Design (DDD), com foco na escalabilidade e agilidade. Pode auxiliar no entendimento de como DDD pode influenciar a modelagem de dados e a arquitetura de microsserviços. É **essencial** para o Tema 3.

**Artigo 9:** "Repercussão de Arquitetura Limpa e a Norma ISO/IEC 25010 na Mantenibilidade de Aplicativos Android"
*   **Resumo:** Avalia o impacto da arquitetura limpa na mantenibilidade de aplicativos, utilizando métricas da norma ISO/IEC 25010. Útil para entender como a arquitetura limpa pode melhorar a qualidade interna de aplicativos móveis e como ela se relaciona com a persistência de dados.

**Artigo 10:** "Um Método para o Desenvolvimento de Software Baseado em Microsserviços"
*   **Resumo:** Propõe um método para desenvolvimento de software baseado em microsserviços, com foco na modularização e granulação de serviços.  Pode ser útil para compreender a aplicação de microsserviços na prática e como eles se relacionam com a persistência de dados em um ambiente distribuído. **Importante** para o Tema 3.

**Artigo 11:** "Explorando Estilos Arquiteturais para Servir Sistemas Inteligentes"
*   **Resumo:** Explora padrões arquiteturais para sistemas inteligentes, avaliando diferentes cenários e *trade-offs*. Pode auxiliar no entendimento de padrões de comunicação para microsserviços com persistência de dados.

**Artigo 12:** "Uma Avaliação Qualitativa de Estilos Arquiteturais a partir das Características da Arquitetura Evolutiva"
*   **Resumo:** Avalia diferentes estilos arquiteturais (monolítico, microsserviços, baseado em eventos e serverless) com base nas características da arquitetura evolutiva. Pode auxiliar a entender os diferentes estilos e suas vantagens e desvantagens quando combinados com a persistência de dados. **Relevante** para o Tema 3.

**Artigo 13:** "Análise Comparativa entre Ferramentas de Desenvolvimento de Aplicativos Móveis Multiplataforma"
*   **Resumo:** Compara ferramentas de desenvolvimento de aplicativos móveis multiplataforma como React Native e Ionic, usando a norma ISO/IEC 25000 como base. Pode auxiliar na compreensão de como ferramentas de desenvolvimento podem impactar a arquitetura e a implementação de persistência de dados.

**Artigo 14:** "Estudo Teórico da Arquitetura de Software Model View Controller"
* **Resumo**: Explora o padrão MVC (Model-View-Controller) e suas variações, identificando linguagens e frameworks que o utilizam. Útil para entender um dos padrões arquiteturais mais utilizados no desenvolvimento de software.

**Artigo 15**: "Refactoring the Whitby Intelligent Tutoring System for Clean Architecture"
*   **Resumo**: Apresenta a refatoração de um sistema de tutoria inteligente para uma arquitetura limpa, utilizando princípios SOLID e inversão de dependências. Útil para entender a aplicação prática da arquitetura limpa em sistemas complexos e a importância do desacoplamento e injeção de dependência. **Relevante** para o Tema 2.

**Artigo 16**: "Um estudo sobre diferentes arquiteturas para aplicações mobile na nuvem"
*  **Resumo**: Analisa e compara três arquiteturas de software para aplicações móveis hospedadas na nuvem, com foco em modificabilidade, confiabilidade e segurança. Pode auxiliar na compreensão das diferentes abordagens de arquitetura em nuvem.

**Artigo 17**:  "Uma Infra-estrutura de Software para Apoiar a Construção de Arquiteturas de Software Baseadas em Componentes"
*   **Resumo**: Apresenta uma infra-estrutura de software para apoiar a construção de arquiteturas de software baseadas em componentes (DBC). Pode auxiliar no entendimento de como construir arquiteturas modulares e reutilizáveis, relevantes para microsserviços.

**Artigo 18**:  "Uma Avaliação Qualitativa de Estilos Arquiteturais a partir das Características da Arquitetura Evolutiva"
*  **Resumo**: Avalia diferentes estilos arquiteturais, incluindo microsserviços e monolítico, com base nas características da arquitetura evolutiva, e como cada estilo facilita a adaptação e a mudança. **Muito relevante** para o Tema 3.

**Artigo 19**: "Get Your Hands Dirty on Clean Architecture"
*  **Resumo**: Aborda a construção de aplicações "limpas" usando exemplos de código em Java, focando em arquitetura de software e enfatizando a manutenibilidade, flexibilidade e adaptabilidade. **Relevante** para o Tema 2 e para entender conceitos de arquitetura.

**Artigo 20**: "Análise Comparativa entre Ferramentas de Desenvolvimento de Aplicativos Móveis Multiplataforma utilizando Características da ISO/IEC 25010 por meio da Implementação de um Cenário Pré-definido"
*  **Resumo**: Apresenta uma análise comparativa entre ferramentas de desenvolvimento de aplicativos móveis, utilizando critérios de qualidade da norma ISO/IEC 25000. Pode auxiliar na compreensão de como ferramentas podem influenciar a arquitetura e a qualidade do software.

**Artigo 21**: "Desenvolvimento de um Aplicativo Utilizando o Framework Flutter e Arquitetura Limpa"
*  **Resumo**: Aborda o desenvolvimento de um aplicativo móvel utilizando Flutter e a Arquitetura Limpa, com foco na organização do código e separação de responsabilidades. Pode auxiliar no entendimento da aplicação da arquitetura limpa em aplicações móveis.

**Artigo 22**: "Estudo Exploratório sobre o Design da Usabilidade Integrado ao Design da Arquitetura do Software"
* **Resumo**: Explora a integração da usabilidade no design da arquitetura de software, identificando desafios e soluções alternativas. Pode auxiliar no entendimento da importância da usabilidade em conjunto com a arquitetura.

**Artigo 23**: "Explorando Estilos Arquiteturais para Servir Sistemas Inteligentes"
* **Resumo**: Apresenta a exploração de padrões arquiteturais para sistemas inteligentes, com foco em como servir modelos de aprendizado de máquina de forma escalável e eficiente. Pode auxiliar no entendimento de como arquiteturas podem se relacionar com a inteligência artificial.

**Artigo 24**: "Repercussão de Arquitetura Limpa e a Norma ISO/IEC 25010 na Mantenibilidade de Aplicativos Android"
* **Resumo**: Apresenta um estudo sobre como a arquitetura limpa e a norma ISO/IEC 25010 podem influenciar a manutenibilidade de aplicativos Android. Pode auxiliar no entendimento de como a arquitetura pode impactar a manutenção de software.

**Artigo 25**: "Árvores Binárias Evolutivas de Arquitetura para Rastreamento da História de Sistemas Legados"
*  **Resumo**: Apresenta uma abordagem para rastrear a história da evolução de sistemas legados através da arquitetura. Pode auxiliar na compreensão de como a arquitetura evolui ao longo do tempo.

**Artigo 26**: "Uma História da Engenharia de Software: Complexidade, Inovação e um Caminho a Seguir"
*   **Resumo**: Apresenta uma narrativa detalhada da evolução da engenharia de software, destacando as figuras-chave e os impactos no campo. Pode auxiliar no entendimento da evolução da área de engenharia de software.

**Artigo 27**: "Um Método para o Desenvolvimento de Software Baseado em Microsserviços"
* **Resumo**: Propõe um método para o desenvolvimento de software baseado em microsserviços, abrangendo desde a elicitação de requisitos até a implantação e monitoramento. Pode auxiliar no entendimento prático do desenvolvimento de microsserviços. **Relevante** para o Tema 3.

**Artigo 28**: "Aplicando MDE e Clean Architecture para Gerenciar Periféricos Móveis em Android"
*  **Resumo**: Aborda a aplicação de Clean Architecture para o gerenciamento de periféricos móveis em Android, com foco na reutilização e na separação de responsabilidades. Pode auxiliar no entendimento prático da aplicação da arquitetura limpa em um cenário específico.

**Artigo 29**: "Refactoring the Whitby Intelligent Tutoring System for Clean Architecture"
* **Resumo**: Apresenta a refatoração de um sistema de tutoria inteligente para uma arquitetura limpa, utilizando princípios SOLID e inversão de dependências. Pode auxiliar no entendimento da aplicação prática da arquitetura limpa em sistemas complexos.

### 4. Metodologia

*   **Aplicação Prática:** Desenvolver uma pequena aplicação para exemplificar os conceitos estudados, utilizando um *framework* que suporte injeção de dependência (ex: Spring Boot para Java, .NET Core para C#, ou algum framework para Node.js).
*   **Análise Comparativa:** Utilizar uma análise comparativa entre diferentes arquiteturas, abordagens de persistência, migrações e injeção de dependência para identificar vantagens e desvantagens.
*   **Estudos de Caso:** Realizar entrevistas com profissionais que participaram de projetos de migração para entender os desafios e soluções adotadas na prática.
*  **Foco em Métricas:** Utilizar métricas de software para avaliar o impacto da arquitetura e da migração na qualidade e desempenho do sistema.
