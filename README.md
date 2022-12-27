# ![](https://github.com/alletsc/data_cleaning/blob/main/assets/img/telecomunication.png?raw=true)

## **🧑🏽‍💼 Análise e limpeza de dados de telecomunicações 🐍**

## ✅ **Objetivo**

## 🧹 Etapas de Limpeza de Dados

<!-- - Remover dados irrelevantes -->
<!-- - Remover dados duplicados -->
- Converter dados para o tipo correto
<!-- - Corrigir erro de digitação -->
<!-- - Remover dados que não fazem sentido e espaços em branco ou zeros desncecessários -->
- Tratar dados faltantes
- Tratar outliers
<!-- - Padronizar e normalizar dados -->

## Ferramentas na pasta `utils`

Esta pasta contém 3 arquvios com funções que podem ser usadas para limpar os dados.

Os arquivos e funções são:

- conversao_dados.py

  - `convert_to_string`:
  - `convert_to_int`:
  - `convert_to_datetime`:
  - `convert_to_factor`:

- trat_outliers.py

  - `remove_outliers`:
  - `replace_outliers_with_fences`:
  - `getOveview`:

- valores_ausentes.py

  - ` func_calc_percentual_valores_ausentes`: Calcula o percentual de valores ausentes em um DataFrame
  - `func_calc_percentual_valores_ausentes_linha`: calcula o percentual de linhas com valores ausentes
  - `func_calc_percentual_valores_ausentes_coluna`: calcula valores ausentes por coluna
  - `fix_missing_ffill`: Imputação de valores ausentes usando forward fill (preenchimento progressivo) - preenche com o próximo valor válido
  - `fix_missing_bfill`: Imputação de valores ausentes usando backward fill (preenchimento regressivo) - preenche com o último valor válido
  - `fix_missing_median`: Imputação usando a mediana
  - `fix_missing_value`: Preenche valor NA
  - `drop_duplicates`: Remove linhas duplicadas
  - `drop_rows_with_missing_values`: Drop de linhas com valores ausentes
  - `drop_columns`: Drop de colunas

## 🚨 **Problema de negócio**


## Conclusões




**Recomendações do Analista de Dados**:



