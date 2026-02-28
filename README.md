### Projeto EBOOK: Guia Mestre do Data Warehouse 🚀

ℹ️  **NOTE:** Este repositório contém a documentação e os prompts utilizados para a criação de um guia técnico completo sobre a construção de um Data Warehouse moderno, utilizando a Arquitetura Medallion e as melhores práticas de engenharia de dados.

Projeto com o objetivo de gerar um ebook digital detalhado sobre pipelines de dados, desde a extração de fontes heterogêneas até a carga final em Postgres. Todos os prompts seguem abaixo.

📕 [Clique aqui para ler o ebook finalizado](./output/ebook_data_warehouse.pdf)

#### 💻 Tecnologias utilizadas no projeto
*  **Notebooklm**: Geração de conteúdo técnico e estruturação de tópicos.
*  **Nano Banana 2**: Criação de ilustrações conceituais de arquitetura de dados.
*  **PowerPoint**: Diagramação e design visual.

#### 🧠 Prompts

**ChatGPT：**

| Ação | Prompt |
| :--- | :--- |
| Título | Crie um título de ebook sobre o tema criação de data warehouse, o ebook ´do nicho de programação o subnicho é engengaria de dados, o tútulo deve se épico e curto, e tenha uma temática mais organizacional e profissional. |
| Conteúdo | faça um texto para ebook, com foco em Data Warehouse, listando todo o passo a passo para criação de um data warehouse utilizando como fonte dos dados (oracle, api, csv, microsoft server), ferramenta de ETL o Dagster ou Pentaho, para pipeline o Apache Airflow banco DW o postgres. Preciso que seja detalhado e explique todo o passo a passo, os pontos de atenção e todas as melhores práticas para um desenvolvimento e manutenção trtanquila.
{REGRAS}

Explique sempre de uma maneira simples
Deixe o texto enxuto
Sempre traga exemplo de script ou fluxo real
Sempre deixe um título sugestivo por tópico |

**Nano Banana 2:**

| Ação | Prompt |
| :--- | :--- |
| Visual | Create a premium executive-style ebook cover for the title “Data Warehouse Profissional: A Engenharia por Trás da Estratégia de Dados”.
The design should resemble a high-level business editorial cover, similar to Harvard Business Review aesthetics. Clean, sophisticated, and intellectually powerful.
Visual concept: a minimalist and elegant representation of enterprise data architecture — a refined central geometric structure symbolizing a data warehouse core, with subtle structured connections radiating outward (representing strategic data flow and decision layers). The elements should be abstract, precise, and architectural — not flashy or overly technical.
Style: editorial, executive, corporate sophistication.

Color palette: deep navy or charcoal background, refined gold or muted copper accent lines, soft neutral typography space.

Composition: strong central focal point, generous negative space, perfectly balanced layout.

Lighting: subtle gradient depth, soft shadowing, understated luxury.

Mood: authority, strategy, intelligence, governance, executive-level thinking.

Avoid: busy diagrams, 3D clutter, futuristic sci-fi visuals, gaming aesthetics, excessive glow effects.
Format: vertical ebook cover, high resolution, ultra-sharp, print-ready quality, clean background with ample space for title and subtitle. |

#### ✨ Features
*  **Arquitetura Medallion**: Detalhamento das camadas Bronze, Silver e Gold [1, 2].
*  **Governança de Dados**: Padronização de nomenclatura (prefixos COD, DAT, VAL) [3].
*  **Scripts Reais**: Exemplos de SQL para limpeza, deduplicação e carga em lote [4].

#### 📚 Materiais
*  Imagens utilizadas em `assets` [2].
*  Ebook gerado durante o processo em `output` [2].

#### 🛠️ Instruções de execução
Utilize os prompts listados acima nas ferramentas sugeridas para gerar o material base. Utilize uma ferramenta de edição de documentos (PowerPoint, InDesign ou Canva) para a diagramação final, seguindo a estrutura de 8 páginas sugerida.

#### 👨‍💻 Expert

**Seu Nome Aqui**  
[GitHub](https://github.com/juanfagner) | [LinkedIn](https://linkedin.com/in/juan-garcia-bi)

⌨️ com 💜 por [Juan Garcia]