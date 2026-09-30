
# 🩸 Caderno Temático de Estudos: Anemia Falciforme

> Projeto prático desenvolvido para o desafio da **DIO (Digital Innovation One)**, aplicando Inteligência Artificial com **NotebookLM** para aprendizagem ativa, curadoria e organização do conhecimento em saúde e biologia.

---

## 🎯 Contexto e Objetivos

* **Tema Escolhido:** Anemia Falciforme (Fisiopatologia, Diagnóstico e Aspectos Genéticos).
* **Motivação:** Compreender em profundidade os mecanismos biológicos, os sintomas clínicos e a importância da detecção precoce de uma das doenças hereditárias mais prevalentes no mundo.
* **Objetivos de Aprendizagem:**
  - Mapear a alteração genética (mutação na hemoglobina HbA -> HbS) e seu impacto estrutural nas hemácias.
  - Compreender as principais complicações associadas (crises de falcização, vaso-oclusão, dores crônicas e suscetibilidade a infecções).
  - Estruturar um guia prático de estudos baseado estritamente em fontes científicas validadas.

---

## 📂 Curadoria de Fontes

As fontes abaixo foram selecionadas de repositórios oficiais e científicos, servindo de base de conhecimento para o caderno no NotebookLM:

1. 📄 **Protocolo Clínico e Diretrizes Terapêuticas da Doença Falciforme** – *Ministério da Saúde (Brasil)*
2. 📄 **Nota Técnica Nº 2/2025-SVSA/MS** – *Ministério da Saúde / Secretaria de Vigilância em Saúde e Ambiente*
3. 🌐 **About Sickle Cell Disease** – *Sickle Cell Disease Association of America* | [Acessar Link](https://sicklecelldisease.org/about-sickle-cell-disease/)

---

## 🔬 Engenharia de Prompts & "Cicatrizes" (Troubleshooting)

Documentação do processo de extração, refinamento de respostas e solução de problemas usando o NotebookLM.

### 🧪 Evolução dos Prompts

* **Prompt Inicial (Simples):**
  > *"O que é a Anemia Falciforme?"*
  * **Resultado:** A IA trouxe uma definição geral: doença genética e hereditária autossômica recessiva (genótipo homozigótico **HbSS**), citando a substituição do ácido glutâmico por valina na cadeia beta-globina do gene *HBB*, gerando a hemoglobina anormal **HbS**.
  * **Referências Utilizadas:** *Mapeamento Molecular e Clínico da Anemia Falciforme: Da Fisiopatologia às Mudanças Regulatórias e Fronteiras Terapêuticas.*

* **Prompt Refinado (Específico e Estruturado):**
  > *"Com base estrita nas fontes fornecidas, explique a causa genética da Anemia Falciforme, detalhando a mutação de ponto que ocorre na cadeia beta da hemoglobina e explique como a desoxigenação leva à deformação das hemácias em formato de foice."*
  * **Resultado:** A IA correlacionou de forma sequencial o mecanismo fisiopatológico:  
    `Mutação no gene HBB → Produção de HbS → Desoxigenação (hipóxia) → Polimerização da HbS → Deformação da hemácia em foice`.
  * **Referências Utilizadas:** *Mapeamento Molecular e Clínico da Anemia Falciforme: Da Fisiopatologia às Mudanças Regulatórias e Fronteiras Terapêuticas.*

### ⚠️ Dificuldades e Soluções (Troubleshooting)

* **Desafio Encontrado:** Inicialmente, a IA forneceu explicações com linguagem genérica ao descrever as complicações clínicas, sem encadear a causa biológica com os sintomas.
* **Como foi Resolvido:** Reformulei o prompt solicitando explicitamente a relação causal em formato lógico e estritamente baseado nos documentos do caderno, evitando interpolações de senso comum sobre anemia.

---

## 📖 Miniguia de Estudo (Entrega Final)

### 📌 Resumo Estruturado do Assunto

1. **Etiologia e Genética:**
   - A Anemia Falciforme é uma doença autossômica recessiva provocada por uma mutação de ponto no gene *HBB*.
   - Indivíduos homozigotos (**HbSS**) expressam a forma grave da doença, enquanto heterozigotos (**HbAS**) possuem o traço falciforme (geralmente assintomáticos).

2. **Fisiopatologia e Deformação Celular:**
   - Em condições de baixa tensão de oxigênio (hipóxia), a Hemoglobina S (**HbS**) se polimeriza formando longos filamentos.
   - Isso altera o citoesqueleto da hemácia, conferindo-lhe o formato de foice (falcização), tornando-a rígida e com vida útil reduzida (hemólise).

3. **Manifestações Clínicas e Complicações:**
   - **Vaso-oclusão:** Obstrução de microvasos sanguíneos causando crises dolorosas intensas.
   - **Síndrome Torácica Aguda:** Complicação grave que requer intervenção imediata.
   - **Suscetibilidade a Infecções:** Decorrente do autoesplenismo (comprometimento funcional do baço).

---

### 📚 Glossário de Conceitos

| Termo | Definição |
| :--- | :--- |
| **HbS (Hemoglobina S)** | Variante mutante da hemoglobina responsável pela Anemia Falciforme. |
| **Falcização** | Processo no qual as hemácias perdem seu formato bicôncavo maleável e assumem formato de foice. |
| **Vaso-oclusão** | Bloqueio do fluxo sanguíneo provocado pela agregação de hemácias rígidas/falcizadas nos microvasos. |
| **Traço Falciforme (HbAS)** | Condição do indivíduo portador de apenas um alelo mutado; não desenvolve a doença, mas pode transmiti-la. |

---

## 🚀 Prompts Reutilizáveis para Revisão

```text
Atue como um professor de hematologia e elabore um mapa conceitual em texto relacionando os termos: Mutação HBB, Polimerização de HbS, Falcização, Vaso-oclusão e Crise de Dor.
```

## 🛠️ Ferramentas Utilizadas

* **[NotebookLM]([https://notebooklm.google.com/](https://notebook.google.com/notebook/6f8c1c00-0729-4eb5-9b52-f020af7355db):** Leitura sintética, extração de conceitos e engenharia de prompts.
* **GitHub:** Documentação, controle de versão e exibição do portfólio.

---

✍️ **Desenvolvido por:** Eduardo de Santana Costa  
🔗 **LinkedIn:** [Acessar Perfil](https://www.linkedin.com/in/eduardo-de-santana-costa-b9779baa/)


