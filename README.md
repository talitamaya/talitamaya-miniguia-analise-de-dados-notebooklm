# 📚 Miniguia de Análise de Dados e Business Intelligence

## 🎯 Contexto e objetivos

Este projeto foi desenvolvido como parte de um desafio da DIO com o objetivo de utilizar Inteligência Artificial como ferramenta de aprendizagem ativa.

O tema escolhido foi Análise de Dados e Business Intelligence, área pela qual tenho interesse profissional.

O objetivo foi utilizar o NotebookLM para organizar fontes confiáveis, formular perguntas estratégicas, testar diferentes prompts e consolidar os conhecimentos obtidos em um miniguia de estudos.

## 📖 Fontes utilizadas

1. Microsoft Learn — O que é o Power BI
2. Microsoft Learn — Introdução à análise de dados
3. Microsoft Learn — Preparar e visualizar dados com Power BI
4. IBM — Business Intelligence

## 🤖 Engenharia de Prompts

Durante o projeto foram testados diferentes prompts para:

- Explorar os conceitos iniciais;
- Comparar conceitos;
- Criar perguntas de revisão;
- Organizar os conhecimentos;
- Consolidar o conteúdo em um miniguia.

### Prompt inicial
"Explique o que é Power BI."

### Problema encontrado
Falta de exemplos, falta de organização na estrutura da resposta, falta de glossário. Resposta muito ampla e sem direcionamento.

**Power BI** é um conjunto de ferramentas de análise e visualização de dados da Microsoft que permite conectar-se facilmente a diversas fontes de dados, transformar e moldar informações e apresentá-las em relatórios e painéis (*dashboards*) interativos[1]. A plataforma visa transformar dados brutos em insights visualmente atraentes e impactantes, dando suporte a decisões confiáveis e orientadas por dados em toda a empresa[1][3].

### Principais Componentes do Power BI

O fluxo de trabalho do Power BI engloba diferentes ferramentas voltadas para etapas específicas da análise e do compartilhamento[4][5]:

* **Power BI Desktop**: Indicado para a **criação e modelagem de relatórios**[4]. Permite a conexão com mais de 100 fontes de dados (como arquivos, bancos de dados, serviços em nuvem e páginas da Web), o tratamento e transformação de dados via Editor do Power Query, a criação de modelos e medidas com DAX e a utilização de mais de 30 visuais internos e personalizados[5].
* **Serviço do Power BI (** **Power BI Service** **)**: Plataforma na nuvem voltada para **colaboração e compartilhamento** em equipe[4][5]. Oferece recursos como organização em *workspaces*, publicação e distribuição de aplicativos, criação de painéis em tempo real, agendamento de atualizações de dados e implementação de segurança em nível de linha (RLS)[5].
* **Power BI Mobile**: Aplicativos otimizados para a **exibição e visualização** de relatórios e painéis em dispositivos móveis (telefones e tablets)[4].

### Recursos e Ferramentas Especializadas

* **Construtor de Relatórios do Power BI (** **Power BI Report Builder** **)**: Utilizado para criar **relatórios paginados**, adequados para impressão ou formatos estruturados, como faturas[6][7].
* **Servidor de Relatórios do Power BI**: Solução para manter e gerenciar **relatórios em ambiente local** (*on-premises*), mantendo a opção de migrar para a nuvem posteriormente[6][7].
* **Copilot no Power BI**: Recursos de inteligência artificial integrados que auxiliam no desenvolvimento de modelos semânticos, na criação automática de relatórios e resumos, e na exploração de dados utilizando linguagem natural[8].* **

### Prompt aprimorado

"Com base exclusivamente nas fontes deste notebook, explique o que é Power BI para uma estudante iniciante em Análise de Dados. Organize a resposta em conceito, finalidade, principais recursos e exemplo de utilização."

### Resultado e aprendizado

Melhor descrição e organização dos conceitos, acréscimo de exemplos para sustentar os pontos citados e facilitar o entendimento de uma pessoa iniciante na área. Definir o público e o formato torna a resposta mais adequada.
### **1\. Conceito**

O **Power BI** é um ecossistema e solução de software da Microsoft composto por diferentes aplicações, como o **Power BI Desktop**, o **Serviço do Power BI** (em nuvem) e os aplicativos **Power BI Mobile**[1][2]. Ele permite conectar-se facilmente a diversas fontes de dados, transformar e moldar essas informações brutas e criar relatórios visuais e interativos[2][3].

---

### **2\. Finalidade**

A principal finalidade do Power BI é transformar dados em relatórios e painéis (*dashboards*) impactantes, fornecendo suporte para tomadas de decisões confiáveis e orientadas por dados em toda a empresa[3][4].

Para quem está iniciando em Análise de Dados, o Power BI atua como a ferramenta prática para executar todo o ciclo de análise: desde a importação e limpeza do dado bruto até a construção do modelo de dados e a entrega de visualizações para os gestores e equipes[1].

---

### **3\. Principais Recursos**

Os recursos do Power BI são divididos de acordo com as ferramentas do seu ecossistema[1][2]:

* **Power BI Desktop (focado em criação e modelagem):**
  * **Conexão ampla de dados:** Conecta-se a mais de 100 fontes de dados diferentes, incluindo arquivos, bancos de dados e serviços em nuvem[2].
  * **Tratamento de dados:** Utiliza o Editor do Power Query para realizar a limpeza, transformação e moldagem dos dados[2].
  * **Modelagem e cálculos:** Permite estruturar relacionamentos entre tabelas e criar cálculos personalizados utilizando a linguagem DAX (*Data Analysis Expressions*)[2].
  * **Visualização:** Disponibiliza mais de 30 elementos visuais internos e personalizados para compor os relatórios[2].
* **Serviço do Power BI (plataforma em nuvem para colaboração):**
  * **Compartilhamento:** Utiliza *workspaces* para trabalho em equipe e permite publicar aplicativos para distribuir painéis e relatórios[1][2].
  * **Automação:** Permite agendar atualizações automáticas dos dados, configurar assinaturas por e-mail, criar alertas e gerenciar a segurança (como a Segurança em Nível de Linha - RLS)[2].
* **Power BI Mobile:**
  * Oferece aplicativos otimizados para smartphones e tablets, permitindo consultar e interagir com relatórios em qualquer lugar[1].
* **Recursos Avançados e Inteligência Artificial:**
  * **Copilot no Power BI:** Assistente de IA que auxilia na modelagem de dados, criação de relatórios, geração de resumos e permite interagir com os dados via linguagem natural[5].
  * **Relatórios Paginados:** Permite criar relatórios altamente formatados para impressão ou exportação (como faturas) usando o Construtor de Relatórios do Power BI[6].

---

### **4\. Exemplo de Utilização**

Considere o fluxo de trabalho típico de uma analista de dados ao acompanhar as vendas de uma empresa[1][2]:

1. **Conexão e Limpeza:** A analista abre o **Power BI Desktop**, conecta-se aos arquivos de vendas e utiliza o Editor do Power Query para tratar inconsistências e remover dados duplicados[2][7].
2. **Modelagem e Visualização:** Em seguida, constrói os relacionamentos entre as tabelas, cria medidas em DAX para calcular o faturamento e desenha um relatório com gráficos interativos de vendas por região e período[2][8].
3. **Publicação e Compartilhamento:** Com o relatório pronto, ela o publica no **Serviço do Power BI** dentro de um *workspace* compartilhado para a equipe de negócios[1][2].
4. **Acompanhamento Móvel:** Os gestores abrem o aplicativo **Power BI Mobile** em seus celulares para verificar os indicadores atualizados antes de uma reunião de planejamento[1].* **

## 📚 Miniguia de Estudos
**10 perguntas de revisão** elaboradas com base nas fontes do notebook para testar e fixar seus conhecimentos. 

---

### 📝 Questões de Revisão: Análise de Dados, BI e Power BI

1. **Conceito de Business Intelligence (BI):** Como as fontes definem Business Intelligence (BI) e qual é o seu objetivo principal nas organizações?
2. **BI vs. Business Analytics (BA):** Qual é a diferença entre Business Intelligence (BI) e Business Analytics (BA)?
3. **Componentes do Power BI:** QUAIS são os três componentes/aplicativos principais que formam o ecossistema do Power BI e qual é a função básica de cada um?
4. **Recursos do Power BI Desktop:** Cite pelo menos três tarefas essenciais de análise e criação de relatórios que são realizadas especificamente no **Power BI Desktop**.
5. **Colaboração e Segurança no Serviço do Power BI:** Quais recursos presentes no **Serviço do Power BI** (*Power BI Service*) auxiliam no compartilhamento, colaboração em equipe e segurança dos dados?
6. **Infraestrutura de Dados em BI:** Qual é o papel de um *data warehouse* e de um mecanismo *OLAP* na sustentação das análises de BI?
7. **Relatórios Paginados:** O que são *relatórios paginados* no Power BI, qual ferramenta é utilizada para desenvolvê-los e para qual tipo de documento eles são recomendados?
8. **Power Query e DAX:** Qual é a função específica do **Editor do Power Query** e para que serve a linguagem **DAX** no Power BI?
9. **Inteligência Artificial (Copilot):** De que maneiras o **Copilot no Power BI** auxilia o analista durante o desenvolvimento de modelos e relatórios?
10. **Benefícios e Boas Práticas de BI:** Indique dois benefícios que a adoção de BI traz para as empresas e duas boas práticas recomendadas para garantir o sucesso da sua implementação.

---

Com base nas fontes do notebook, apresento a seguir o **Mapa de Conhecimentos em Análise de Dados e Business Intelligence**, estruturado em níveis progressivos — do conceito fundamental até as tecnologias e práticas mais avançadas — demonstrando como cada camada se conecta e sustenta a anterior.

---

```text
 ┌──────────────────────────────────────────────────────────────────────────┐
 │ NÍVEL 1: FUNDAMENTOS DE DADOS E ANÁLISE                                 │
 │ (Coleta, Conexão e Processo Analítico)                                  │
 └────────────────────┬─────────────────────────────────────────────────────┘
                      │
                      ▼
 ┌──────────────────────────────────────────────────────────────────────────┐
 │ NÍVEL 2: INFRAESTRUTURA E BUSINESS INTELLIGENCE (BI)                     │
 │ (Armazenamento, Modelagem Multidimensional e Análise Descritiva)         │
 └────────────────────┬─────────────────────────────────────────────────────┘
                      │
                      ▼
 ┌──────────────────────────────────────────────────────────────────────────┐
 │ NÍVEL 3: ECOSSISTEMA E EXECUÇÃO COM POWER BI                            │
 │ (Tratamento, Modelagem DAX, Visualização e Colaboração na Nuvem)        │
 └────────────────────┬─────────────────────────────────────────────────────┘
                      │
                      ▼
 ┌──────────────────────────────────────────────────────────────────────────┐
 │ NÍVEL 4: RECURSOS ESPECIALIZADOS E ANALYTICS AVANÇADO                   │
 │ (Relatórios Paginados, IA/Copilot, Fabric e Análise Preditiva/Prescritiva)│
 └──────────────────────────────────────────────────────────────────────────┘
```

---

### Nível 1: Fundamentos de Dados e Análise (Básico)
* **Processo de Análise de Dados**: Compreensão das etapas, funções e tarefas necessárias para examinar e transformar dados brutos em respostas e insights nos quais as pessoas confiam para agir.
* **Tipos de Análise de Dados**: Exploração das diferentes abordagens analíticas (como a análise descritiva) para responder a perguntas específicas de negócios.
* **Origens e Fontes de Dados**: Identificação e extração de dados armazenados em arquivos locais, bancos de dados relacionais, bancos de dados NoSQL e serviços online.

---

### Nível 2: Business Intelligence - BI (Intermediário)
* **Conceito e Finalidade do BI**: Conjunto de processos tecnológicos para coletar, gerenciar e analisar dados organizacionais (históricos, atuais, internos e de terceiros) com o objetivo de fornecer uma visão descritiva do negócio e guiar decisões estratégicas.
* **Arquitetura e Repositórios de Dados**:
  * **Data Warehouse**: Sistema central que agrega e consolida dados de múltiplas fontes para apoiar a análise e a criação de relatórios.
  * **Mecanismo OLAP**: Tecnologia que suporta consultas multidimensionais e cálculos analíticos complexos.
  * **Data Lakehouse**: Evolução da gestão de dados que resolve desafios entre data warehouses e data lakes.
* **Cultura e Benefícios de BI**: Consolidação de informações em *dashboards* para criar eficiência operacional, monitorar metas e acelerar a tomada de decisões.

---

### Nível 3: Ecossistema e Prática com Power BI (Aplicado)
* **Visão Geral do Ecossistema**: Solução da Microsoft que transforma dados em relatórios e painéis interativos.
* **Power BI Desktop (Desenvolvimento)**:
  * Conexão com mais de 100 fontes de dados.
  * Tratamento e transformação de dados utilizando o **Editor do Power Query**.
  * Modelagem de dados, criação de relacionamentos e fórmulas analíticas com **DAX**.
  * Design visual com mais de 30 tipos de visuais internos e personalizados.
* **Serviço do Power BI (Colaboração em Nuvem)**:
  * Organização do trabalho em equipe por meio de *workspaces*.
  * Distribuição de relatórios e *dashboards* via aplicativos e agendamento de atualizações.
  * Configuração de controle de acesso e segurança em nível de linha (RLS).
* **Power BI Mobile**: Acesso e navegação otimizados para dispositivos móveis.

---

### Nível 4: Recursos Especializados e Plataformas Avançadas (Avançado)
* **Relatórios e Ambientes Especializados**:
  * **Relatórios Paginados**: Desenvolvidos no *Power BI Report Builder* para criar documentos estruturados e adequados para impressão, como faturas.
  * **Servidor de Relatórios do Power BI**: Manutenção de relatórios no ambiente local (*on-premises*) para organizações que exigem armazenamento interno.
* **Inteligência Artificial Integrada (Copilot no Power BI)**:
  * Permite interagir com dados utilizando consultas em linguagem natural.
  * Auxilia na preparação, modelagem de dados semânticos e criação automática de relatórios e resumos de insights.
* **Evolução Analítica e Plataforma Unificada**:
  * **Business Analytics (BA) e Análise Preditiva/Prescritiva**: Expansão do BI descritivo tradicional para análises voltadas ao futuro e recomendações de ações.
  * **Microsoft Fabric**: Plataforma única que atende a todas as necessidades de análise de ponta a ponta da empresa.

---

### 🔄 Como os Conceitos se Relacionam no Fluxo Prático

1. **Os Dados Brutos (Nível 1)** são extraídos de diversas fontes e precisam passar por uma **Infraestrutura Estruturada de BI (Nível 2)**, como *Data Warehouses* ou *Lakehouses*, para garantir a qualidade e a centralização das informações.
2. Com os dados organizados, o analista utiliza uma **Ferramenta como o Power BI (Nível 3)** para aplicar o processo analítico: transforma os dados no *Power Query*, cria modelos e regras em *DAX*, constrói o relatório no *Desktop* e o publica na nuvem para a equipe.
3. Para atender a necessidades corporativas complexas **(Nível 4)**, a organização expande o uso incorporando IA (*Copilot*) para gerar insights rápidos, utiliza *Microsoft Fabric* para integrar toda a cadeia de dados e adota análises preditivas para antecipar cenários de negócio.*

### Análise de Dados

A **Análise de Dados** é o processo de examinar, organizar e transformar dados brutos em insights significativos e confiáveis, permitindo que as pessoas e organizações tomem atitudes fundamentadas.
Sua principal finalidade é dar suporte a decisões estratégicas e orientadas por dados** (*data-driven*) em todos os níveis da empresa.

### Business Intelligence

**Business Intelligence (BI)** é um conjunto de processos tecnológicos para coletar, gerenciar e analisar dados organizacionais, transformando dados brutos em insights significativos que orientam as estratégias e operações de uma empresa[1].

### Power BI

O **Power BI** é a ferramenta da Microsoft para transformar dados em relatórios e painéis interativos que oferecem suporte a decisões empresariais confiáveis[1][9]. O ecossistema é composto principalmente pelo **Power BI Desktop** (focado em conexão a mais de 100 fontes de dados, transformação via Power Query e modelagem com DAX), pelo **Serviço do Power BI** (plataforma na nuvem para colaboração em *workspaces* e compartilhamento) e pelos **aplicativos Power BI Mobile**

### Relação entre os conceitos

* **Análise de Dados como disciplina abrangente:** Representa o processo analítico geral para transformar perguntas de negócios em respostas e *insights* acionáveis[2].
* **BI como infraestrutura e arcabouço:** O BI fornece a estrutura tecnológica e organizacional necessária para identificar, armazenar e gerenciar os dados da empresa de forma contínua[4]. Além disso, engloba o *Business Analytics* (BA), que é um subconjunto focado em análises prescritivas e voltadas para o futuro[4].
* **Power BI como ferramenta de execução:** O Power BI funciona como a tecnologia prática que executa o processo de análise de dados dentro da estrutura de BI[1][7]. Ele conecta as fontes de dados brutas, realiza a limpeza e modelagem no Power BI Desktop e disponibiliza os relatórios para colaboração no Serviço do Power BI[5][6].

**Fontes utilizadas nesta seção:**

* *Introdução à análise de dados da Microsoft - Training | Microsoft Learn*[1][2]
* *O que é o Power BI? - Power BI | Microsoft Learn*[5][6]
* *Preparar e visualizar dados com o Microsoft Power BI DP-605T00 - Training | Microsoft Learn*[7]
* *What Is Business Intelligence (BI)? | IBM*[4]* *

## 📖 Glossário

| Conceito | Definição |
|---|---|
| Análise de Dados | ... |
| Business Intelligence | ... |
| Power BI | ... |
| Dashboard | ... |
| Modelagem de Dados | ... |
| Visualização de Dados | ... |

## 💡 O que aprendi

O desenvolvimento deste projeto me permitiu compreender melhor os conceitos relacionados à análise de dados e Business Intelligence, além de praticar o uso de Inteligência Artificial como ferramenta de aprendizagem.

Também percebi a importância de elaborar prompts claros, fornecer contexto e avaliar criticamente as respostas geradas pela IA.

## 🔄 Prompts reutilizáveis

### Para resumo
"Com base exclusivamente nas fontes deste notebook, crie um mapa de conhecimentos sobre Análise de Dados e Business Intelligence. Organize os conceitos do mais básico ao mais avançado e explique brevemente a relação entre eles. Destaque os conceitos que uma pessoa iniciante deveria compreender primeiro."

### Para revisão
"Com base exclusivamente nas fontes deste notebook, crie 10 perguntas de revisão sobre Análise de Dados, Business Intelligence e Power BI. As perguntas devem variar entre conceitos, compreensão e aplicação prática. Não apresente as respostas inicialmente. Depois que eu responder, corrija minhas respostas utilizando somente as informações presentes nas fontes."

### Para comparação
"Com base exclusivamente nas fontes deste notebook, compare Análise de Dados, Business Intelligence e Power BI. Organize a resposta em uma tabela contendo: conceito, objetivo, principais atividades ou recursos, aplicação e relação com os outros conceitos. Não acrescente informações que não estejam sustentadas pelas fontes."

### Para aprofundamento
"Com base exclusivamente nas fontes deste notebook, explique o Power BI para uma estudante iniciante em Análise de Dados. Organize a resposta em: conceito, finalidade, principais recursos, etapas de utilização e exemplo prático. Indique as fontes utilizadas para cada parte da resposta."

## 🚀 Próximos passos

Continuar meus estudos em Excel, Power BI, SQL, Python e outras ferramentas relacionadas à área de Dados.
