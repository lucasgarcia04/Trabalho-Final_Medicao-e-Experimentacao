# Plano de Experimento – Scoping e Planejamento

## 1. Identificação Básica

## 1.1 Título do Experimento
Avaliação do Impacto do Uso de IA em IDEs na Produtividade de Desenvolvedores Iniciantes

## 1.2 ID / Código
EXP-IA-PROD-001  

## 1.3 Versão do Documento e Histórico de Revisão
- **v1.0 – (23/11/2025)**: Criação inicial do documento e topicos 1 e 2.
- **v2.0 – (24/11/2025)**: Criação dos topicos 3, 4, 5 e 6.
- **v3.0 – (28/11/2025)**: Criação dos topicos 7, 8 , 9.
- **v4.0 – (01/12/2025)**: Criação dos topicos 10, 11 e 12. 
- **v5.0 – (05/12/2025)**: Criação dos topicos 13.
- **v6.0 – (11/12/2025)**: Criação dos topicos 14, 15, 16, 17, 18 e 19.  

## 1.4 Datas
- **Data de criação:** 23/11/2025  
- **Última atualização:** 11/12/2025    

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

---

# 7. Modelo conceitual e hipóteses

## 7.1 Modelo conceitual do experimento
Acredita-se que **o uso de uma ferramenta de IA de assistência à programação (GitHub Copilot)** influencia positivamente a produtividade de desenvolvedores iniciantes, reduzindo o tempo necessário para concluir tarefas e possivelmente melhorando a qualidade do código.

**Esquema conceitual:**
Uso de IA em IDEs -> Aumento de produtividade -> Possível redução de erros -> Aumento de qualidade

O modelo assume que:
- A IA sugere trechos de código automaticamente.
- Isso reduz esforço cognitivo e tempo.
- Pode gerar códigos com menor quantidade de erros.
- Logo, o fator uso da IA impacta diretamente nas variáveis de produtividade e qualidade.

---

## 7.2 Hipóteses formais (H0 e H1)

### Hipótese sobre produtividade (tempo)
- **H0:** Não há diferença significativa no tempo de conclusão entre os grupos.  
- **H1:** O grupo com IA conclui as tarefas em menos tempo.

### Hipótese sobre qualidade (defeitos)
- **H0:** Não há diferença significativa no número de defeitos entre os grupos.  
- **H1:** O grupo com IA produz menos defeitos.

### Hipótese sobre esforço percebido
- **H0:** Não há diferença significativa no esforço percebido entre os grupos.  
- **H1:** O grupo com IA relata menos esforço percebido.

---

## 7.3 Nível de significância e poder estatístico
- **Nível de significância adotado:** α = 0,05  
- **Poder estatístico esperado:** entre 0,70 e 0,80  
- **Justificativa:** amostra pequena típica de ambientes acadêmicos; o experimento detecta apenas efeitos médios ou grandes.

---

# 8. Variáveis, fatores, tratamentos e objetos de estudo

## 8.1 Objetos de estudo
- Tarefas de programação de pequena e média complexidade (funções, correção de bugs).
- Código produzido pelos participantes.
- Indicadores registrados (tempo, defeitos, esforço etc.).

---

## 8.2 Sujeitos / participantes
- Estudantes de Engenharia de Software ou desenvolvedores juniores.
- Experiência prática limitada.
- Perfil homogêneo em nível de habilidade inicial.

---

## 8.3 Variáveis independentes (fatores) e seus níveis

| Fator | Descrição | Níveis |
|-------|-----------|--------|
| Uso da IA | Uso de ferramenta de apoio à programação | Sem IA (controle), Com IA (Copilot) |

---

## 8.4 Tratamentos (condições experimentais)

| Tratamento | Descrição |
|------------|-----------|
| T0 – Sem IA | Participantes resolvem a tarefa sem qualquer sugestão automática. |
| T1 – Com IA | Participantes resolvem a mesma tarefa com GitHub Copilot habilitado. |

---

## **Tabela — Fatores, Tratamentos e Combinações**

Como há apenas **um fator com dois níveis**, as combinações possíveis são:

| Fator | Tratamento | Código | Combinação |
|--------|-------------|---------|------------|
| Uso da IA | Sem IA | T0 | F1–Nível 0 |
| Uso da IA | Com IA | T1 | F1–Nível 1 |

---

## 8.5 Variáveis dependentes (respostas)

| Variável | Tipo | Descrição |
|----------|-------|------------|
| Tempo de execução | Quantitativa contínua | Tempo total (em minutos) para concluir a tarefa. |
| Número de defeitos | Quantitativa discreta | Quantidade de erros encontrados na inspeção posterior. |
| Esforço percebido | Qualitativa ordinal | Autoavaliação do esforço (escala Likert 1–5). |
| Linhas de código | Quantitativa discreta | Total de LOC produzidas. |
| Taxa de aceitação das sugestões | Quantitativa contínua | Percentual de sugestões do Copilot aceitas (somente grupo T1). |

---

## 8.6 Variáveis de controle / bloqueio

| Variável | Justificativa |
|----------|---------------|
| Complexidade da tarefa | Mantida igual para todos para evitar vieses. |
| Ambiente de desenvolvimento | Todos usam o mesmo IDE/linguagem. |
| Tempo máximo permitido | Garante igualdade de condições. |
| Perfil dos participantes | Todos iniciantes, reduzindo variação de habilidade. |

---

## 8.7 Variáveis de confusão potenciais

| Possível Confundidor | Risco causado |
|----------------------|---------------|
| Familiaridade prévia com IA | Pode favorecer o grupo tratamento. |
| Diferenças individuais de habilidade | Pode distorcer tempo ou qualidade. |
| Motivação e fadiga | Afetam esforço e performance. |
| Ruído no ambiente | Diminui foco e afeta produtividade. |

---

# 9. Desenho experimental

## 9.1 Tipo de desenho
- **Desenho completamente randomizado entre sujeitos**

Justificativas:
- Evita que um participante execute a mesma tarefa 2 vezes (efeito de aprendizado).
- Simples de implementar.
- Minimiza fadiga.

---

## 9.2 Randomização e alocação
- Distribuição aleatória dos participantes usando planilha, random.org ou script simples.
- Tamanho dos grupos balanceado.
- Participantes não escolhem grupo.

---

## 9.3 Balanceamento e contrabalanço 

### Balanceamento
- Aplicar **pré-questionário** para medir experiência e familiaridade com programação/IA.  
- Criar **faixas de experiência** e realizar **alocação aleatória dentro de cada faixa** (estratificação).  
- Manter **mesmo número de participantes** por grupo (A: sem IA, B: com IA).  
- Padronizar ambiente: mesmas máquinas, IDE, linguagem e instruções.  
- Realizar **tarefa de aquecimento** curta antes da sessão principal.

### Contrabalanço
- Não aplicável ao desenho entre-sujeitos (cada participante faz apenas um tratamento).  
- Mitigações adicionais:
  - Sessão única + tarefa única.
  - Proibir compartilhamento de soluções entre participantes.
  - Usar tarefa de prática para reduzir efeito de aquecimento.

---

## 9.4 Número de grupos e sessões 

### Grupos
- 2 grupos:
  - Grupo A (Controle): sem IA.
  - Grupo B (Tratamento): com IA.

### Sessões
- 1 sessão por participante, duração estimada de 30–40 min.  
- Antes: 10–15 min para consentimento + pré-questionário.  
- Tarefa de aquecimento: 5–10 min.

### Justificativa
- Evita efeitos de ordem/aprendizagem entre condições.  
- Reduz fadiga e facilita logística.  
- Adequado quando há risco de carry-over.

### Amostra recomendada
- Mínimo: 16–20 participantes (8–10 por grupo).  
- Ideal: 24–40 participantes (12–20 por grupo).  
- Diferença máxima entre grupos: Nenhuma.

### Logística
- Sessões em blocos de 1 hora.  
- Se houver várias máquinas, rodar em paralelo mantendo proporção A:B equilibrada.  
- Aplicador acompanha cada bloco e registra eventuais problemas.

---

# **Tabela geral - Variáveis do experimento**

| Nome da Variável | Tipo | Independente/Dependente/Controle | Descrição | Unidade |
|------------------|------|----------------------------------|-----------|---------|
| Uso da IA | Categórica | Independente | Presença ou ausência do Copilot | N/A |
| Tempo de execução | Contínua | Dependente | Tempo para concluir a tarefa | Minutos |
| Número de defeitos | Discreta | Dependente | Total de defeitos identificados | Contagem |
| Esforço percebido | Ordinal | Dependente | Autoavaliação do esforço | Escala 1–5 |
| Linhas de código | Discreta | Dependente | Total de linhas escritas | LOC |
| Taxa de aceitação de sugestões | Contínua | Dependente | % de sugestões aceitas | Percentual |
| Complexidade da tarefa | Categórica | Controle | Tarefa padrão para todos | N/A |
| Ambiente de desenvolvimento | Categórica | Controle | IDE e linguagem usados | N/A |
| Experiência do participante | Categórica | Controle/Bloqueio | Todos iniciantes | N/A |
| Tempo máximo permitido | Contínua | Controle | Tempo limite da sessão | Minutos |

---

# 10. População, sujeitos e amostragem

## 10.1 População-alvo
A população-alvo são **desenvolvedores iniciantes** (0–2 anos de experiência) que programam regularmente em linguagens como **JavaScript ou Python** em ambientes de desenvolvimento comuns (VS Code). Representa estudantes de computação, estagiários e juniores atuando em equipes de desenvolvimento web ou backend.

## 10.2 Critérios de inclusão
- Idade ≥ 18 anos.  
- Saber programar ao menos em nível introdutório.  
- Ter feito ao menos 1 disciplina de programação.  
- Conseguir realizar leitura e escrita básica de código.  
- Disponibilidade de 1 hora para o experimento.  

## 10.3 Critérios de exclusão
- Experiência profissional > 2 anos em desenvolvimento.  
- Uso frequente (> 3 meses) de GitHub Copilot ou ferramentas de IA de autocompletar.  
- Participantes que já fizeram piloto ou versões anteriores do experimento.  
- Conflitos de interesse (ex.: monitor responsável pela tarefa).  

## 10.4 Tamanho da amostra planejado
- **Total planejado:** 20 a 30 participantes.  
- **Por grupo:** 10–15 por grupo (A: Sem IA, B: Com IA).  
- Justificativa: tamanho suficiente para detectar efeitos médios, dentro das restrições de tempo e disponibilidade.

## 10.5 Método de seleção / recrutamento
- **Amostra de conveniência**, recrutada entre:
  - estudantes de cursos de computação,  
  - comunidade acadêmica,  
  - alunos voluntários de disciplina de Engenharia de Software.  
- Recrutamento via e-mail, grupo de turma ou formulário.

## 10.6 Treinamento e preparação dos sujeitos
- Guia rápido sobre:
  - IDE utilizada (VS Code),
  - linguagem da tarefa,
  - regras do experimento,
  - exemplos simples de entrada e saída.  
- Tarefa de aquecimento de 5–10 min para nivelar familiaridade com o ambiente.

---

# 11. Instrumentação e protocolo operacional

## 11.1 Instrumentos de coleta
- **Questionário pré-experimento**: coleta experiência, familiaridade e covariáveis.
- **VS Code + extensão de log**: registra tempo de digitação, comandos, pausas, checkpoints.
- **Formulário pós-experimento**: coleta percepção, dificuldade, confiança.
- **Planilha de controle do pesquisador**: horário de início/fim, problemas técnicos.
- **Repositório Git**: usado para armazenar soluções finais e medir métricas objetivas.

## 11.2 Materiais de suporte
- Roteiro impresso com instruções.  
- Guia rápido da tarefa (descrição + exemplos de entrada/saída).  
- Checklist para administradores.  
- Script padronizado de instruções verbais.  

## 11.3 Procedimento experimental (passo a passo)

### Fluxograma operacional (ASCII)
   <img width="329" height="776" alt="image" src="https://github.com/user-attachments/assets/13e20682-e739-4718-a6ec-85a4f271f74c" />


### Roteiro detalhado
1. Apresentação, convite e assinatura do termo de consentimento.  
2. Aplicação do pré-questionário.  
3. Classificação por experiência e alocação aleatória dentro das faixas para Grupo A/B.  
4. Explicação padronizada do ambiente e regras.  
5. Execução da tarefa de aquecimento (5–10 min).  
6. Início da tarefa principal (30–40 min) com o ambiente configurado:  
   - Grupo A: GitHub Copilot desativado.  
   - Grupo B: GitHub Copilot ativado.  
   - Logs coletados automaticamente.  
7. Finalização da tarefa no tempo limite.  
8. Aplicação do questionário pós-experimento.  
9. Salvamento seguro dos arquivos e logs.  
10. Encerramento e agradecimento.

---

## 11.4 Plano de piloto
- Sim, haverá piloto.  
- Participantes: 2–3 estudantes que **não** farão parte da amostra final.  
- Objetivos:
  - medir viabilidade do tempo,  
  - validar instruções e clareza da tarefa,  
  - testar logs e instrumentos.  
- Ajustes possíveis:
  - refinamento da tarefa,
  - ajustes no tempo,
  - melhoria na clareza das instruções,
  - correção de falhas técnicas.

---

# 12. Plano de análise de dados (pré-execução)

## 12.1 Estratégia geral de análise
- Avaliar diferenças entre grupos A e B em relação a:
  - produtividade (tempo para completar),  
  - qualidade da solução,  
  - taxa de erros/sucessos,  
  - percepção subjetiva (esforço e dificuldade).  
- Responder às perguntas:
  - O Copilot aumenta produtividade de iniciantes?  
  - Afeta a qualidade ou somente a velocidade?  
  - Como os usuários percebem a ferramenta?

## 12.2 Métodos estatísticos planejados
- Teste t para dois grupos (se distribuição normal).  
- Mann–Whitney para dados não normais.  
- ANOVA de 1 fator (grupo A vs B) se houver múltiplas métricas.  
- Correlação entre experiência prévia e desempenho.  
- Regressão linear simples/múltipla para controlar covariáveis (ex.: experiência).

## 12.3 Tratamento de dados faltantes e outliers
- Dados faltantes:
  - Remoção de participantes que não concluírem a tarefa.  
  - Interpolação não será utilizada (risco de viés).  
- Outliers:
  - Identificação via boxplot e z-score.  
  - Outliers serão analisados individualmente e marcados; podem ser removidos se houver justificativa (falha técnica, interrupção externa).

## 12.4 Análise de dados qualitativos
- Respostas abertas serão analisadas via:
  - codificação temática inicial,  
  - categorização (ex.: facilidade, dificuldade, frustração, percepção de ajuda),  
  - contagem de frequência e citações representativas.  
- Comentários serão usados para complementar interpretações quantitativas.

---

# 13. Avaliação de validade (ameaças e mitigação)

## 13.1 Validade de conclusão
- **Ameaças:**
  - Baixo poder estatístico devido ao tamanho reduzido da amostra.
  - Violação de suposições dos testes estatísticos (normalidade, homocedasticidade).
  - Medidas imprecisas de produtividade ou qualidade.
- **Mitigações:**
  - Assegurar tamanho de amostra compatível com os testes planejados.
  - Testar normalidade e escolher métodos robustos quando necessário (ex.: Mann–Whitney).
  - Padronizar instrumentos de coleta e revisar métricas no estudo piloto.
  - Registrar todos os procedimentos para reduzir erros de medida.

---

## 13.2 Validade interna
- **Ameaças:**
  - **Selection:** diferenças pré-existentes entre os participantes de cada grupo.
  - **History:** influências externas durante a realização do experimento (interrupções, conversas, distrações).
  - **Maturation:** aprendizado natural durante a atividade pode afetar o desempenho.
  - **Instrumentation:** variações no registro, aplicação das tarefas ou ferramentas.
- **Mitigações:**
  - Randomização dos participantes entre os grupos A e B.
  - Ambientação controlada e aplicação padronizada do experimento.
  - Utilização de tarefas únicas e de curta duração para reduzir maturação.
  - Mesmos instrumentos e logs para todos os participantes.
  - Ajustes feitos por meio do piloto para reduzir inconsistências.

---

## 13.3 Validade de constructo
- **Ameaças:**
  - Métricas de "produtividade", "qualidade" e "esforço" não representarem corretamente os conceitos teóricos.
  - Possíveis interpretações diferentes da tarefa ou das instruções pelos participantes.
  - Participantes tentarem adivinhar a hipótese, influenciando o comportamento.
- **Mitigações:**
  - Definir operacionalizações claras (ex.: tempo, taxa de erros, completude da solução, escalas de esforço).
  - Refinar instruções após o piloto, garantindo clareza e interpretação consistente.
  - Não revelar a hipótese do estudo, reduzindo viés de expectativa.
  - Usar múltiplas métricas para reforçar validade convergente.

---

## 13.4 Validade externa
- **Ameaças:**
  - Amostra limitada a estudantes iniciantes, dificultando generalização para profissionais.
  - Tarefas simples e curtas que não representam totalmente atividades reais de desenvolvimento.
  - Ambiente experimental mais controlado que cenários reais de programação.
- **Mitigações:**
  - Descrever detalhadamente características da amostra, permitindo comparações com outros contextos.
  - Selecionar tarefas representativas, mesmo que simplificadas.
  - Discutir explicitamente limitações de generalização e sugerir replicações futuras em contextos profissionais.

---

## 13.5 Resumo das principais ameaças e estratégias de mitigação

| Tipo de validade | Ameaças principais | Estratégias de mitigação |
|------------------|-------------------|---------------------------|
| **Conclusão** | Baixo poder; violação de suposições; medidas imprecisas | Aumento da amostra; testes robustos; padronização dos instrumentos |
| **Interna** | Seleção; history; instrumentation; maturation | Randomização; ambiente controlado; tarefas curtas; estudo piloto |
| **Constructo** | Métricas inadequadas; ambiguidades; viés de expectativa | Definições claras; revisão das instruções; ocultar hipóteses |
| **Externa** | Amostra limitada; tarefas pouco realistas; ambiente artificial | Descrição do contexto; tarefas representativas; replicações futuras |

---

# 14. Ética, privacidade e conformidade

## 14.1 Questões éticas
Esta seção trata das principais preocupações referentes ao bem-estar dos participantes e ao cuidado necessário para garantir que a participação no experimento seja justa, segura e livre de coerção. Como o estudo envolve estudantes iniciantes, é importante garantir que eles não se sintam pressionados, intimidados ou expostos.

### Possíveis questões éticas
- **Pressão implícita para participar:** como o experimento pode ocorrer dentro de uma disciplina, alguns estudantes podem achar que precisam participar para agradar o professor ou evitar prejuízo.
- **Sensação de avaliação:** iniciantes podem interpretar a atividade como uma “prova”, gerando desconforto ou ansiedade.
- **Incentivos inadequados:** recompensas muito grandes podem influenciar a decisão, afetando a voluntariedade.
- **Risco de exposição:** métricas de desempenho (tempo, erros, qualidade do código) podem acabar revelando alunos com mais dificuldade.

### Tratamento das questões éticas
Cada risco ético será mitigado de forma clara e formal:
- A participação será **voluntária**, sem qualquer impacto em notas ou avaliação da disciplina.
- Reforço explícito de que o desempenho não será usado como medida de competência.
- Garantia de que nenhum resultado individual será divulgado ou comparado com outros participantes.
- Qualquer incentivo será discreto e não coercitivo (ex.: horas complementares).
- Todos os dados divulgados serão anônimos, assegurando proteção da identidade.

---

## 14.2 Consentimento informado
Antes de iniciar o experimento, cada participante receberá um termo de consentimento que explica, de forma clara e acessível:

- o objetivo geral do estudo,
- como o experimento será conduzido,
- quais riscos e desconfortos mínimos podem existir,
- quais benefícios ou aprendizados o participante pode obter,
- que a participação é voluntária e que o participante pode desistir a qualquer momento,
- que os dados serão usados apenas para fins acadêmicos e sempre de forma anônima.

O consentimento será documentado por assinatura física ou digital, garantindo que o participante esteja plenamente informado.

---

## 14.3 Privacidade e proteção de dados
O experimento coleta dados sensíveis sobre desempenho e perfil dos participantes, portanto é necessário definir mecanismos formais para proteger essas informações.

### Dados coletados
Serão coletados:
- tempo para execução das tarefas,
- métricas do código produzido,
- registros automáticos (logs),
- respostas a questionários antes e depois do experimento,
- informações básicas de experiência prévia em programação.

### Proteção aplicada
Para garantir segurança:
- Todos os dados serão anonimizados com identificadores aleatórios.
- O repositório com dados será privado, com acesso restrito apenas à equipe autorizada.
- Nenhum código ou log conterá nome ou identificação pessoal.

### Retenção e descarte
- Os dados serão armazenados por até **12 meses**, apenas para auditoria e análise.
- Após esse período, ocorrerá descarte seguro ou anonimização completa e irreversível.

---

## 14.4 Aprovações necessárias
Para que o experimento seja formalmente autorizado, algumas instâncias precisam avaliar e aprovar o plano:

- **Comitê de Ética em Pesquisa**, caso o estudo se enquadre nas normas da instituição.
- **DPO (Data Protection Officer)**, para garantir conformidade com LGPD.
- **Orientadores e professores** responsáveis pela disciplina.
  
**Status atual:** aguardando envio dos documentos para análise.

---

# 15. Recursos, infraestrutura e orçamento

## 15.1 Recursos humanos e papéis
Esta seção define quem são os responsáveis por cada etapa do experimento:

- **Pesquisador principal:** concebe o experimento, conduz a análise e toma decisões principais.
- **Assistente de aplicação:** organiza as sessões, apoia tecnicamente os participantes e resolve problemas operacionais.
- **Avaliador de qualidade:** verifica os códigos e artefatos produzidos pelos participantes.
- **Participantes:** estudantes voluntários que executarão as tarefas experimentais.

---

## 15.2 Infraestrutura técnica necessária
O experimento depende de ambiente técnico padronizado para garantir consistência entre sessões:

- laboratório equipado com computadores semelhantes,
- acesso ao GitHub Copilot para o grupo experimental,
- uso do VS Code como IDE padrão,
- scripts automáticos de coleta de métricas,
- um repositório Git privado para armazenar dados.

---

## 15.3 Materiais e insumos
Além da infraestrutura técnica, alguns materiais e documentos devem estar prontos antes da execução:

- termos de consentimento,
- questionários de pré e pós-experimento,
- máquinas configuradas com todos os softwares,
- eventuais licenças temporárias para uso do Copilot,
- planilhas e checklists para padronizar o processo.

---

## 15.4 Orçamento e custos estimados
O custo do experimento é considerado baixo, porque envolve principalmente esforço humano:

- licenças do Copilot (caso necessárias),
- cerca de 10–20 horas da equipe para preparo e aplicação,
- eventuais cópias impressas de documentos.

O orçamento total é mínimo, sendo mais associado ao tempo das pessoas envolvidas.

---

# 16. Cronograma, marcos e riscos operacionais

## 16.1 Macrocronograma
Este cronograma mostra a sequência geral das atividades até a análise dos resultados:

| Marco | Data prevista |
|-------|---------------|
| Finalização do plano | Semana 1 |
| Preparação dos instrumentos | Semana 2 |
| Execução do piloto | Semana 3 |
| Ajustes pós-piloto | Semana 4 |
| Sessões do experimento | Semana 5 |
| Análise inicial dos dados | Semana 6 |

---

## 16.2 Dependências entre atividades
Algumas atividades só podem ocorrer depois de outras estarem concluídas:

- O piloto só pode ocorrer após os instrumentos estarem concluídos.
- O treinamento dos facilitadores só ocorre após a aprovação ética.
- A execução depende da configuração das máquinas e da confirmação dos participantes.
- A análise só é possível após o encerramento da coleta de dados.

---

## 16.3 Riscos operacionais e contingência
O experimento pode enfrentar imprevistos; por isso, planos de contingência foram preparados:

- **Baixa adesão:** iniciar recrutamento mais cedo e oferecer mais horários.
- **Problemas técnicos:** manter computadores extras e backups do ambiente.
- **Falhas nos scripts de logging:** validar no piloto e ter coleta manual como alternativa.
- **Interferências externas:** reservar sala protegida de ruídos e interrupções.

---

# 17. Governança do experimento

## 17.1 Papéis e responsabilidades
A governança define claramente quem faz o quê, evitando confusões ou lacunas:

- **Pesquisador principal:** supervisiona tudo e toma as decisões-chave.
- **Assistente técnico:** garante que o ambiente esteja funcionando corretamente.
- **Monitor da sala:** cuida da disciplina e da padronização durante a aplicação.
- **Avaliador externo:** assegura que os resultados e análises sejam revisados de forma objetiva.

---

## 17.2 Ritos de acompanhamento pré-execução
Para manter alinhamento entre todos os envolvidos, serão realizadas:

- reuniões semanais antes do piloto,
- uma revisão completa dos instrumentos antes da primeira sessão,
- um checkpoint pós-piloto para ajustes,
- uma validação final antes do início do experimento.

---

## 17.3 Controle de mudanças no plano
Caso seja necessário modificar qualquer elemento do experimento:

- a mudança será registrada como *issue* no repositório,
- discutida em reunião rápida,
- submetida à aprovação do orientador,
- documentada na nova versão oficial do plano.

---

# 18. Plano de documentação e reprodutibilidade

## 18.1 Repositórios e convenções
Para garantir organização e rastreabilidade, todo o material ficará em um repositório Git:

- pastas organizadas por função (instrumentos, scripts, dados brutos, análises),
- nomes padronizados seguindo `exp-IA-2025_<artefato>`.

---

## 18.2 Templates e artefatos padrão
A equipe utilizará modelos e artefatos consistentes para facilitar a aplicação do experimento:

- questionários padronizados,
- termo de consentimento,
- checklist operacional,
- script unificado de logging.

---

## 18.3 Empacotamento para replicação futura
Para permitir que outros pesquisadores reproduzam o experimento:

- haverá um README com instruções completas,
- scripts automatizados de setup serão disponibilizados,
- datasets anonimizados serão preservados,
- um guia detalhando como repetir a análise estatística será incluído.

---

# 19. Plano de comunicação

## 19.1 Públicos e mensagens-chave
A comunicação garante que cada grupo receba as informações necessárias:

- **Participantes:** objetivo, datas, regras e voluntariedade.
- **Professores/orientador:** riscos, cronograma e status das etapas.
- **Equipe técnica:** requisitos de equipamentos e prazos.

---

## 19.2 Canais e frequência
As comunicações ocorrerão por:

- e-mail e Discord/Teams semanalmente,
- reunião rápida antes da execução,
- canal privado diário para equipe técnica.

---

## 19.3 Pontos de comunicação obrigatórios
Alguns eventos exigem comunicação formal e imediata:

- aprovação ética,
- liberação dos instrumentos finais,
- mudanças em datas ou logística,
- encerramento e próximos passos.

---

# 20. Critérios de prontidão (Definition of Ready)

## 20.1 Checklist de prontidão
Antes de iniciar o experimento, tudo isso deve estar concluído:

- plano aprovado,
- instrumentos validados no piloto,
- ambiente técnico configurado,
- consentimento pronto,
- cronograma confirmado,
- participantes recrutados,
- comunicações enviadas.

---

## 20.2 Aprovações finais
Para começar a execução, será necessário o aceite final de:

- pesquisador principal,
- orientador,
- técnico de infraestrutura.

---


