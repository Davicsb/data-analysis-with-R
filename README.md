# Atividade AB2-2 – Estatística Aplicada em R

Este repositório contém o script em **RMarkdown** utilizado na Atividade **AB2-2** de Estatística.

O objetivo é aplicar conceitos de **inferência estatística** sobre a mesma base utilizada na AB1.1, incluindo:

- Intervalo de confiança para a média  
- Testes de hipótese para média (uma e duas amostras)  
- Teste de proporções (duas amostras)  
- ANOVA de um fator  
- Correlação entre variáveis numéricas  
- Regressão linear simples  
- Transformação de dados (logarítmica)

---

## Arquivos

- `AB2-2_Atividade.Rmd` – arquivo principal em RMarkdown com todo o código, textos e interpretações.
- `data/data_ADAPTED.csv` – base de dados utilizada nas análises.

---

## Requisitos

- **R** instalado  
- **RStudio** (opcional, mas recomendado)  
- Pacotes básicos do R (já usados no próprio RMarkdown), como:
  - `knitr`
  - `stats` (carregado por padrão)

---

## Como executar

1. Clone o repositório ou faça o download dos arquivos.
2. Certifique-se de que o arquivo `data_ADAPTED.csv` está no mesmo diretório indicado no `setwd()` ou ajuste o caminho no início do `.Rmd`.
3. Abra o arquivo `AB2-2_Atividade.Rmd` no RStudio.
4. Clique em **Knit** para gerar o relatório em **PDF** ou **HTML**.

Também é possível renderizar direto pelo R:

```r
rmarkdown::render("AB2-2_Atividade.Rmd")
