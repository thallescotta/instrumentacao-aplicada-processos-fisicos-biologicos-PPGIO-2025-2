# [IOA6042] Instrumentação Aplicada a Processos Físicos e Biológicos (2025.2)
---

<!-- Imagem alinhada à esquerda -->
<p align="center">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSHYOnIACPcb9bCeQQ_wbfF9mp5ADlbCIoghtDM6YiLklaBrtEsAxZ-G-y6N3_PNR_tCmw&usqp=CAU"
       alt="Logo CEFET"
       width="360">   <!-- tamanho da logo -->
</p>

**Professor:** Jesse Werner Costa  
**Aluno:** Thalles Cotta Fontainha – **Matrícula PPGIO**: 2410091DIOAMA  

---

## ✅ Atividade 1 - Estatística Descritiva de Dados Experimentais (Solicitado em Aula 1)

**Dados**  
- **Tabela 1 - 72 alunos:** Idade (anos), Massa (kg), Altura (cm)  
- **Tabela 2 - 30 bancadas:** Medidas de comprimento (cm)

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
- `instrumentacao_1a_lista.ipynb` (Colab/Python) - Importa dados, calcula estatísticas e gera tabelas/gráficos.  
  👉 Versão no GitHub:  
[  `1st_exercise_Intrumentação 2025 Cefet PPGIO InstrFis.ipynb`](https://github.com/thallescotta/instrumentacao-aplicada-processos-fisicos-biologicos-PPGIO-2025-2/blob/main/1st_exercise_Intrumenta%C3%A7%C3%A3o%C2%A02025_Cefet_PPGIO_InstrFis.ipynb)

---

## ✅ Atividade 2 - SRIM/TRIM e Simulação de Hadronterapia (Solicitado em Aula 1)

**Entrega:**  

Versão em PTBR:
https://github.com/thallescotta/instrumentacao-aplicada-processos-fisicos-biologicos-PPGIO-2025-2/blob/main/2nd_Relat%C3%B3rio_exercise_Intrumenta%C3%A7%C3%A3o_2025_Cefet_PPGIO_InstrFis_Template_CEFET_RJ_Pr%C3%A1tica_de_Pesquisa.pdf

Verion in EN:
https://github.com/thallescotta/instrumentacao-aplicada-processos-fisicos-biologicos-PPGIO-2025-2/blob/main/2nd_Report_EN_exercise_Intrumenta%C3%A7%C3%A3o_2025_Cefet_PPGIO_InstrFis_Template_CEFET_RJ_Pr%C3%A1tica_de_Pesquisa.pdf

1. **Introdução** (fundamentos, descrição do software e contexto de hadronterapia)  
2. **Procedimentos de simulação** (materiais, camadas, energias, parâmetros de feixe)  
3. **Resultados** (gráficos, tabelas, discussão)  
4. **Conclusões**  
5. **Referências**

> 💡 Observação: O SRIM/TRIM é distribuído para **Windows**. Para fins didáticos, foi criado o tutorial https://github.com/thallescotta/instrumentacao-aplicada-processos-fisicos-biologicos-PPGIO-2025-2/blob/main/2nd_Tutorial_exercise_Intrumenta%C3%A7%C3%A3o_2025_Cefet_PPGIO_InstrFis.ipynb



---

## ✅ Atividade 3 - FTIR N₂O Irradiação

📦 **Materiais Recebidos – 01/10/2025 (via Grupo WhatsApp)**

No dia **01 de outubro de 2025**, foram compartilhados os seguintes arquivos para a realização da **Atividade 3 – Análise por Espectroscopia FTIR (N₂O)**:

- 📄 `ColumnDensityCalculation-MangumShirley.pdf`  
- 📄 `Fulvio_2009_N2O.pdf`  
- 📄 `Gerakines_2015_8205_808_2_L40.pdf`  
- 📊 `Ices calculations dose v1 Bordalo.xls`  
- 📄 `Ioppolo_N2O_PCCP.pdf`  
- 📄 `Jamieson_N2O_2005_APJ.pdf`  
- 📄 `LapinskiEspectrocopiaN2O.pdf`  
- 📝 `InstrumProcFisBioRoteiroTarefa2.docx`  
- 📄 `InstrumProcFisBioRoteiroTarefa2.pdf`  
- 🗜️ `N2O pure at 12K.zip`  
  - 📁 **`N2O pure at 12K`** (pasta contendo espectros experimentais no formato `.SPA`):
    - `Background, Sam Juin 13 12-48-10 2015 (GMT+02-00).SPA`  
    - `Background, Sam Juin 13 13-59-37 2015 (GMT+02-00).SPA`  
    - `N2O 10K Sam Juin 13 15-56-12 2015.SPA`  
    - `N2O 11K 0.5mbar Sam Juin 13 14-12-32 2015 5.SPA`  
    - `N2O 11K Sam Juin 13 16-33-04 2015 5e9.SPA`  
    - `N2O 11K Sam Juin 13 16-38-10 2015 1e10.SPA`  
    - `N2O 11K Sam Juin 13 16-48-53 2015 5e10.SPA`  
    - `N2O 11K Sam Juin 13 16-54-26 2015 1e11.SPA`  
    - `N2O 11K Sam Juin 13 17-01-33 2015 2.5e11.SPA`  
    - `N2O 11K Sam Juin 13 17-10-48 2015 5e11.SPA`  
    - `N2O 11K Sam Juin 13 17-23-28 2015 1e12.SPA`  
    - `N2O 11K Sam Juin 13 17-51-49 2015 2.5e12.SPA`  
    - `N2O 11K Sam Juin 13 18-04-16 2015 3e12.SPA`  
    - `N2O 11K Sam Juin 13 18-34-30 2015 80K.SPA`  
    - `N2O 80K Sam Juin 13 18-34-30 2015.SPA`  
    - `N2O 120K Sam Juin 13 18-53-42 2015.SPA`  
    - `N2O 11K Sam Juin 13 16-43-49 2015 2.5e10.SPA`  
    - `Ven_Juin_12_15_39_48_2015_test_N2O.SPA`

Estes arquivos correspondem aos espectros de absorção em diferentes temperaturas (10 K, 11 K, 80 K, 120 K) e fluências de irradiação, obtidos no experimento de FTIR com N₂O. Eles serão usados no programa **OMNIC** para análise de bandas, determinação da espessura do gelo e evolução espectral conforme o roteiro.

