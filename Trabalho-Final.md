# Plano de Experimento – Scoping e Planejamento

## 1. Identificação Básica

## 1.1 Título do Experimento
Avaliação do Impacto do Uso de IA em IDEs na Produtividade de Desenvolvedores Iniciantes

## 1.2 ID / Código
EXP-IA-PROD-001  

## 1.3 Versão do Documento e Histórico de Revisão
- **v1.0 – (23/11/2025)**: Criação inicial do documento e topicos 1 e 2.  

## 1.4 Datas
- **Data de criação:** 23/11/2025  
- **Última atualização:** 23/11/2025    

## 1.5 Autores (nome, área, contato)
- **Nome:** Lucas Ferreira Garcia  
- **Área:** Engenharia de Software  
- **Contato:** lucasferreiragarcia04@gmail.com  

## 1.6 Responsável Principal (PI / Dono do Experimento)
- **Responsável:** Lucas Ferreira garcia  
- **Papel:** Estudante de Engenharia de Software

## 1.7 Projeto / Produto / Iniciativa Relacionada
- Pesquisa aplicada em Engenharia de Software  
- Tema relacionado a ferramentas de apoio ao desenvolvimento e produtividade  

---

# 2. Contexto e Problema

## 2.1 Descrição do Problema / Oportunidade
Ferramentas baseadas em inteligência artificial, como o GitHub Copilot, tornaram-se populares para auxiliar desenvolvedores durante a escrita de código. Contudo, ainda há incerteza sobre o quanto essas ferramentas impactam a produtividade real, a qualidade do código e a experiência de desenvolvedores iniciantes, que podem depender excessivamente da ferramenta ou apresentar resultados inconsistentes.  
Este experimento busca medir objetivamente se o uso de IA melhora, prejudica ou não altera a performance desses desenvolvedores na execução de tarefas de programação.

## 2.2 Contexto Organizacional e Técnico
O experimento será realizado no contexto de um curso de Engenharia de Software, com estudantes que possuem experiência básica em desenvolvimento.  
O ambiente técnico inclui:
- Linguagem de programação padrão (ex.: JavaScript)
- Editor de código VS Code
- Ferramentas de controle de versão (Git/GitHub)
- GitHub Copilot para o grupo experimental
- Tarefas simples de implementação e correção de código  

O processo será conduzido em ambiente controlado, com cronometragem e coleta de métricas objetivas e subjetivas.

## 2.3 Trabalhos e Evidências Prévias (Internos e Externos)
- Estudos recentes sugerem que ferramentas de IA podem aumentar a velocidade de escrita de código, porém os resultados variam conforme o nível de experiência do desenvolvedor.  
- Pesquisas acadêmicas indicam que iniciantes podem adotar soluções sem compreender completamente o código gerado pela IA.  
- Documentos internos do curso incluem atividades prévias envolvendo estimativas e produtividade, mas sem uso de IA como variável.  
- Artigos externos relatam aumento médio de 20% a 55% na produtividade quando há familiaridade com a ferramenta (GitHub Next, Microsoft Research, 2023–2024).

## 2.4 Referencial Teórico e Empírico Essencial
O experimento se fundamenta principalmente em:
- **Teorias de produtividade em engenharia de software**, incluindo métricas de esforço, tempo e qualidade.
- **Modelos de qualidade de código**, como complexidade ciclomática, legibilidade e padrões de estilo.
- **Pesquisa sobre ferramentas de apoio ao desenvolvedor**, incluindo assistentes inteligentes baseados em modelos de linguagem.
- **Estudos empíricos de avaliação de práticas de desenvolvimento**, seguindo métodos experimentais controlados.
- **Literatura sobre adoção de IA**, incluindo potenciais vieses, limitações e riscos associados a depender de ferramentas generativas.

---

# 3. Objetivos e Questões (Goal / Question / Metric)

## 3.1 Objetivo Geral (Goal Template – GQM)
**Analisar** o impacto do uso de ferramentas de IA em IDEs para auxílio à programação,  
**com o propósito de** avaliar sua influência na produtividade e qualidade do código,  
**sob a perspectiva de** desenvolvedores iniciantes e pesquisadores de Engenharia de Software,  
**no contexto de** tarefas controladas de implementação e correção realizadas em ambiente acadêmico.

---

## 3.2 Objetivos Específicos

- **O1:** Medir o impacto do uso de IA no tempo de execução de tarefas de programação.
- **O2:** Avaliar a influência do uso de IA na qualidade do código produzido.
- **O3:** Investigar como o uso de IA afeta a taxa de sucesso na entrega correta das tarefas.
- **O4:** Analisar a percepção dos desenvolvedores iniciantes quanto ao uso da IA em termos de esforço, utilidade e confiança.

---

## 3.3 Questões de Pesquisa (Q)

### Para O1 – Produtividade em tempo
- **Q1.1:** O uso de IA reduz o tempo total necessário para completar tarefas de implementação?  
- **Q1.2:** O uso de IA reduz o tempo necessário para correção de defeitos?  
- **Q1.3:** Há variação significativa entre indivíduos quanto ao ganho/perda de tempo usando IA?

### Para O2 – Qualidade do código
- **Q2.1:** O uso de IA impacta a quantidade de defeitos presentes no código entregue?  
- **Q2.2:** O uso de IA melhora ou piora os resultados das ferramentas de análise estática?  
- **Q2.3:** O uso de IA influencia a complexidade do código produzido?

### Para O3 – Taxa de sucesso
- **Q3.1:** O uso de IA aumenta a proporção de tarefas concluídas corretamente?  
- **Q3.2:** Participantes usando IA entregam mais código funcional em menos tentativas?  
- **Q3.3:** O uso de IA diminui a quantidade de intervenções manuais necessárias para correções?

### Para O4 – Percepção dos iniciantes
- **Q4.1:** Como o uso de IA afeta a percepção de facilidade dos participantes?  
- **Q4.2:** Qual o impacto da IA no esforço cognitivo percebido?  
- **Q4.3:** Participantes consideram que a IA aumenta sua confiança ao programar?

---

## 3.4 Tabela GQM – Objetivos, Perguntas e Métricas

### **Tabela 1 – GQM**

| Objetivo | Pergunta | Métricas Associadas |
|---------|----------|---------------------|
| O1 | Q1.1 | M1 – Tempo total da tarefa; M2 – Tempo por subtarefa |
| O1 | Q1.2 | M1 – Tempo total da tarefa; M3 – Tempo de correção |
| O1 | Q1.3 | M4 – Variação individual de tempo; M1 – Tempo total da tarefa |
| O2 | Q2.1 | M5 – Número de defeitos; M6 – Erros detectados pelo linter |
| O2 | Q2.2 | M6 – Erros do linter; M7 – Score de qualidade |
| O2 | Q2.3 | M8 – Complexidade ciclomática; M7 – Score de qualidade |
| O3 | Q3.1 | M9 – Taxa de sucesso; M5 – Número de defeitos |
| O3 | Q3.2 | M9 – Taxa de sucesso; M10 – Número de tentativas |
| O3 | Q3.3 | M10 – Número de tentativas; M3 – Tempo de correção |
| O4 | Q4.1 | M11 – Escala de facilidade percebida; M12 – Satisfação com a tarefa |
| O4 | Q4.2 | M11 – Esforço percebido; M8 – Complexidade ciclomática |
| O4 | Q4.3 | M12 – Confiança percebida; M11 – Esforço percebido |

---

# **Tabela 2 – Métricas**

| Métrica | Descrição | Unidade |
|---------|-----------|---------|
| **M1 – Tempo total da tarefa** | Tempo entre início e entrega funcional | Minutos |
| **M2 – Tempo por subtarefa** | Tempo por etapa (implementação, testes, revisão) | Minutos |
| **M3 – Tempo de correção** | Tempo gasto exclusivamente corrigindo defeitos | Minutos |
| **M4 – Variação individual de tempo** | Diferença percentual entre participantes | % |
| **M5 – Número de defeitos** | Defeitos encontrados pós-entrega | Contagem |
| **M6 – Erros do linter** | Avisos e erros detectados por análise estática | Contagem |
| **M7 – Score de qualidade** | Índice calculado (lint score) | Pontos |
| **M8 – Complexidade ciclomática** | Complexidade estrutural do código | Valor inteiro |
| **M9 – Taxa de sucesso** | Tarefas concluídas corretamente / total | % |
| **M10 – Número de tentativas** | Quantidade de submissões/refações | Contagem |
| **M11 – Esforço ou facilidade percebida** | Autoavaliação em escala Likert | Pontos (1-10) |
| **M12 – Satisfação/confiança percebida** | Grau de satisfação ou confiança | Pontos (1–10) |

Total de métricas diferentes: **12**.

---

# 4. Escopo e Contexto do Experimento

## 4.1 Escopo funcional / de processo
**Incluído:**
- Tarefas de implementação simples
- Tarefas de correção de bugs
- Análise de métricas de produtividade, qualidade e percepção
- Uso controlado de GitHub Copilot para o grupo experimental

**Excluído:**
- Tarefas complexas de arquitetura
- Projetos de longa duração
- Avaliação de manutenção pós-entrega
- Análise de impacto financeiro ou organizacional

---

## 4.2 Contexto do estudo
- Realizado em **ambiente acadêmico** (curso de Engenharia de Software)  
- Participantes: **desenvolvedores iniciantes** com 6 meses–2 anos de experiência  
- Projeto de **baixa criticidade**, focado em aprendizado e pesquisa  
- Uso de **VS Code**, GitHub e tarefas controladas previamente definidas  

---

## 4.3 Premissas
- Participantes usarão o mesmo computador/ambiente configurado.  
- A versão do GitHub Copilot permanecerá estável durante o experimento.  
- Os participantes não compartilharão respostas entre si.  
- A internet estará funcionando durante todo o experimento.  

---

## 4.4 Restrições
- Tempo limitado (sessão de 1h–2h por participante)  
- Amostra pequena (10–20 participantes)  
- Nem todos podem ter experiência prévia com Copilot  
- Dependência de licença/trial do GitHub Copilot  

---

## 4.5 Limitações previstas
- Resultados podem não generalizar para programadores experientes  
- Ambiente acadêmico não reflete pressões reais do mercado  
- Tarefas curtas não capturam todo o ciclo de desenvolvimento  
- Possibilidade de viés por familiaridade com linguagem/IDE  

---

# 5. Stakeholders e Impacto Esperado

## 5.1 Stakeholders principais
- Estudantes participantes  
- Professor/orientador  
- Pesquisadores em engenharia de software  
- Equipe de produto ou desenvolvimento interessada em IA  
- Instituição acadêmica (coordenação, departamento)  

## 5.2 Interesses e expectativas
- **Estudantes:** aprender impacto real da IA e melhorar desempenho  
- **Professores:** evidências para uso de IA em atividades acadêmicas  
- **Pesquisadores:** dados quantitativos para estudos futuros  
- **Equipes de produto:** avaliar se iniciantes devem ou não usar IA no início da carreira  

## 5.3 Impactos potenciais
- Ajuste nas práticas de ensino (introduzir IA mais cedo ou mais tarde)  
- Decisões sobre permitir ou restringir IA em avaliações  
- Melhoria do entendimento sobre riscos e benefícios da IA  
- Possível revisão de diretrizes de boas práticas para iniciantes  

---

# 6. Riscos, Premissas e Critérios de Sucesso

## 6.1 Riscos de alto nível
- Falhas técnicas no Copilot ou GitHub  
- Indisponibilidade de participantes  
- Dados inconsistentes ou incompletos  
- Viés por diferença de experiência prévia  

---

## 6.2 Critérios de sucesso globais
O experimento será considerado bem-sucedido se:
- Produzir dados confiáveis sobre produtividade e qualidade  
- Conseguir comparar grupos controle e experimental  
- Obter respostas claras para pelo menos 70% das perguntas GQM  
- Lidar com os riscos sem comprometer os resultados finais  

---

## 6.3 Critérios de parada antecipada
- Falta de participantes suficientes  
- Falhas críticas no ambiente técnico  
- Impossibilidade de acessar o Copilot  
- Problemas éticos ou organizacionais no uso da IA  



