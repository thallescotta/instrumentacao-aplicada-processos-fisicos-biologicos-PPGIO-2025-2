# Instrumentação Aplicada a Processos Físicos e Biológicos  
**PPGIO – CEFET/RJ**  
**Professor:** Jesse Costa  
**Aluno:** **Thalles Cotta Fontainha** – **Matrícula PPGIO: 2410091DIOAMA**  

---

# 🧪 Instrumentação Aplicada a Processos Físicos e Biológicos — PPGIO/CEFET-RJ (2025.2)

Repositório da disciplina **Fundamentos de Instrumentação para Experimentos Científicos (IOA6042)**.  
Contém **duas atividades práticas**:

---

## ✅ Atividade 1 — Estatística Descritiva de Dados Experimentais (Aula 1 — 01/09/2025)

**Dados**  
- **Tabela 1 — 72 alunos:** Idade (anos), Massa (kg), Altura (cm)  
- **Tabela 2 — 30 bancadas:** Medidas de comprimento (cm)

**Tarefas**
1. **Tabulação ordenada e agrupada** (definição de classes e contagem de frequências)  
2. **Histogramas**  
   - Idade, Massa e Altura (Tabela 1)  
   - Largura das bancadas (Tabela 2)
3. **Parâmetros de posição**: média, moda, mediana, **média quadrática (RMS)**  
4. **Parâmetros de dispersão**: amplitude, desvio médio, variância, desvio padrão, **largura à meia altura (FWHM)**  
5. **Correlação**  
   - Pares: *(Idade × Altura)*, *(Idade × Massa)*, *(Altura × Massa)*  
   - Cálculo de **covariância** e **coeficiente de correlação linear (r)**

**Notebook**  
- `instrumentacao_1a_lista.ipynb` (Colab/Python) — Importa dados, calcula estatísticas e gera tabelas/gráficos.  
  👉 Versão no GitHub:  
  `1st_exercise_Intrumentação 2025 Cefet PPGIO InstrFis.ipynb`

---

## 🚀 Atividade 2 — SRIM/TRIM e Simulação de Hadronterapia

**Objetivo**  
- Reproduzir um cenário de **irradiação de íons** (He, C, O) em **tecidos equivalentes** e localizar o **pico de Bragg** para um alvo superficial (ex.: tumor a 20 mm).  
- Explorar variação de **energia do feixe** para atingir profundidades específicas e comparar perfis de deposição (antes, no pico e após o alvo).  
- **Criar um segundo cenário** alternativo e **sugerir outras aplicações** de irradiação por íons.

**Entrega sugerida**  
1. **Introdução** (fundamentos, descrição do software e contexto de hadronterapia)  
2. **Procedimentos de simulação** (materiais, camadas, energias, parâmetros de feixe)  
3. **Resultados** (gráficos, tabelas, discussão)  
4. **Conclusões**  
5. **Referências**

> 💡 Observação: O SRIM/TRIM é distribuído para **Windows**. Para fins didáticos, o repositório inclui **notebook em Python** que reproduz **perfis de perda de energia e picos de Bragg** em Linux/Colab usando **stopping power** tabulado/parametrizado.
