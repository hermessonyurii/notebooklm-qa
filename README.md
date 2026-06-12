# 🧠 Caderno Temático: Aprendizagem Ativa, Direitos e Ética em Inteligência Artificial com NotebookLM

Este repositório apresenta o resultado do Desafio de Projeto da **DIO (Digital Innovation One)**, focado em demonstrar o uso do **Google NotebookLM** como ferramenta de aprendizagem. Todo o material base foi estruturado a partir de uma curadoria rigorosa de fontes governamentais, acadêmicas e institucionais.

---

## 🎯 Contexto e Objetivos

O tema escolhido para este caderno de estudos é **"Direitos, Governança, Ética e Integridade Acadêmica no Uso da Inteligência Artificial"**. 

### Nossos Objetivos de Estudo:
1. **Compreender a Regulação Brasileira**: Analisar como a LGPD, o Código de Defesa do Consumidor (CDC) e o Estatuto da Criança e do Adolescente (ECA) protegem o cidadão brasileiro frente à IA.
2. **Mitigar Riscos e Vieses**: Entender as limitações técnicas e sociais das IAs, como o viés algorítmico, a opacidade das "caixas-pretas" e as alucinações.
3. **Aplicar Integridade Acadêmica**: Estudar as regras de uso ético de IAs em pesquisas e trabalhos escolares/universitários, aprendendo a declarar o uso de ferramentas de acordo com diretrizes institucionais (como as da Udesc e da UFBA).
4. **Projeções de Futuro**: Avaliar o impacto socioeconômico da IA nas cidades até 2030 e as recomendações de políticas públicas para segurança.

---

## 📚 Curadoria de Fontes (Uploads no NotebookLM)

Utilizamos **4 documentos oficiais e acadêmicos** para alimentar a base de dados do NotebookLM, garantindo que as respostas da IA sejam precisas e livres de "alucinações":

1. 🏛️ **Guia do Usuário Brasileiro de Inteligência Artificial**
   * *Foco*: Definições de IA, Direitos e Governança no Brasil.
   * *Órgão*: Ministério da Gestão e da Inovação em Serviços Públicos.
2. 📖 **Guia para Uso Ético e Responsável da Inteligência Artificial Generativa (BU Udesc)**
   * *Foco*: Diretrizes de integridade acadêmica, combate ao plágio, letramento em IA e modelos de declaração de uso.
   * *Órgão*: Biblioteca Universitária da Udesc (2025).
3. 🎓 **Artificial Intelligence and Life in 2030 (Stanford University)**
   * *Foco*: Estudo do painel de especialistas sobre como a IA impactará o transporte, a saúde, a segurança pública e os empregos.
   * *Órgão*: Stanford University (AI100).
4. 🇺🇸 **Preparing for the Future of Artificial Intelligence**
   * *Foco*: Políticas públicas de incentivo à pesquisa e ao desenvolvimento responsável de IA.
   * *Órgão*: White House (National Science and Technology Council - NSTC).

---

## 🔬 Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

Ao interagir com o NotebookLM usando essas fontes, registramos nossa experiência de Engenharia de Prompts:

### 🧪 Teste 1: O Prompt Amplo (Falta de Precisão)
* **Prompt digitado:** *"Como posso usar IA na faculdade de acordo com os arquivos?"*
* **Problema:** A IA respondeu de forma genérica, sem separar o que é permitido do que é proibido.
* **Cicatriz de Aprendizado (Troubleshooting):** IAs acadêmicas precisam de delimitações de fronteiras. Sem especificar a fonte institucional, o modelo mistura diretrizes de diferentes países.

### 🧪 Teste 2: O Prompt Estruturado (Resultado Excepcional)
* **Prompt digitado:** *"Com base exclusivamente nas páginas 16 a 18 do Guia da BU Udesc, crie uma tabela de duas colunas listando: (1) O que é PERMITIDO para estudantes ao usar IA e (2) O que é expressamente PROIBIDO. Adicione a responsabilidade final do autor."*
* **Resultado:** O NotebookLM extraiu com precisão:
  * **Permitido**: Apoio na revisão gramatical, formatação de textos (normas ABNT), tradução inicial (com revisão obrigatória) e análise de dados primários.
  * **Proibido**: Elaboração de respostas a questões de provas, copiar e colar conteúdo gerado pela IA direto nos trabalhos e listar a IA como coautora.
  * **Responsabilidade**: "Apenas seres humanos são autores e assumem total responsabilidade pela originalidade do texto."
* **Aprendizado:** A engenharia de prompts na pesquisa exige **delimitar o escopo da fonte** (ex: "com base na BU Udesc") e **exigir o formato da saída** (ex: "tabela de duas colunas").

---

## 📖 Miniguia de Estudo (Entrega Final)

### 📝 Resumo Estruturado do Assunto

#### 1. A Fronteira da Responsabilidade Acadêmica
O uso da IA nas universidades brasileiras deve sempre prever a **Centralidade e Agência Humana**. De acordo com as diretrizes da BU Udesc e da UFBA, os algoritmos devem funcionar como um "assessor" ou "ferramenta de apoio" que acelera tarefas repetitivas. **A IA nunca substitui o julgamento crítico do pesquisador** e não pode constar na autoria ou coautoria de trabalhos científicos.

#### 2. Os Riscos Éticos e Legais no Brasil
Conforme o *Guia do Usuário Brasileiro de IA*, a adoção dessa tecnologia envolve quatro limites fundamentais:
* **Viés Algorítmico**: A IA repete preconceitos históricos presentes nos bancos de dados de treinamento (ex: erros em reconhecimento facial de pessoas negras por falta de representatividade).
* **Opacidade ("Caixa-Preta")**: A dificuldade técnica em auditar ou explicar a lógica interna de funcionamento dos modelos de redes neurais profundas.
* **Alucinação**: A criação estatística de dados falsos ou referências inexistentes que parecem verdadeiras.
* **Privacidade e LGPD**: Dados pessoais, sensíveis ou de pesquisa confidencial **nunca** devem ser inseridos em IAs generativas públicas e proprietárias.

#### 3. Prospecções Sociais (Stanford 2030 & White House)
* **Emprego e Trabalho**: A IA tende a automatizar **tarefas**, e não necessariamente **profissões** inteiras, exigindo a requalificação constante da força de trabalho.
* **Segurança Pública e Regulação**: Drones e veículos autônomos exigem testagem controlada (como *sandboxes* regulatórios) e o desenvolvimento de uma engenharia de segurança de IA robusta para evitar acidentes e proteger a privacidade do cidadão.

---

### 🗂️ Glossário de Conceitos Aprendidos

* **Letramento em IA (AI Literacy)**: Formação continuada em tecnologia para garantir o protagonismo humano no desenvolvimento científico. Suas quatro dimensões são: *Prática* (uso efetivo), *Técnica* (limitações), *Ética* (implicações morais) e *Crítica* (pensamento independente).
* **Alucinação**: Erro gerado por IAs generativas que inventam informações (como citar leis ou livros que não existem) com base apenas em previsões estatísticas de palavras prováveis.
* **Opacidade Intrínseca**: Grau de opacidade em que as relações matemáticas dos algoritmos são tão complexas (redes neurais) que não é possível explicar detalhadamente como chegaram a um resultado.
* **Direito à Explicação**: Garantia dada pela LGPD (Art. 20) e pelo Código de Defesa do Consumidor (CDC) para que os usuários saibam quando estão interagindo com uma IA e possam contestar decisões automatizadas, exigindo revisão humana.

---

### 🔄 Prompts Reutilizáveis para Estudos Futuros

Você pode copiar e colar estes prompts no seu NotebookLM para revisar esse material:

```markdown
Com base nas orientações da BU Udesc, elabore um parágrafo de declaração de uso de IA (Formato Textual Simples) indicando que utilizei o ChatGPT-4 para formatar as referências bibliográficas do meu trabalho de acordo com as normas ABNT.
```

```markdown
Resuma em tópicos quais são os principais deveres do desenvolvedor e do usuário de Inteligência Artificial segundo o "Guia do Usuário Brasileiro de IA".
```

```markdown
Explique, usando exemplos dos relatórios de Stanford e da Casa Branca, quais são os maiores desafios éticos e de segurança no desenvolvimento de carros autônomos.
```

---

## 🛠️ Como replicar este projeto no seu NotebookLM

1. Acesse o [Google NotebookLM](https://notebooklm.google/).
2. Crie um caderno chamado `Estudos de Ética e IA - DIO`.
3. Faça o upload dos PDFs das quatro fontes citadas na seção [Curadoria de Fontes](#-curadoria-de-fontes-uploads-no-notebooklm).
4. Utilize a seção de chats para interagir com o material usando as sugestões de [Prompts Reutilizáveis](#-prompts-reutilizaveis-para-estudos-futuros).

---
Feito com 💙 por [Hermeson Yuri](https://github.com/hermessonyurii).
