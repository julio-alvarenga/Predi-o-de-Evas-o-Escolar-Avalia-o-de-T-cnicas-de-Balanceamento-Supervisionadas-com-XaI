# Predição de Evasão Escolar - INDUSCON 2025

Código do artigo **"Predição de Evasão Escolar: Avaliação de Técnicas de Balanceamento Supervisionadas com Interpretação Local via LIME"** apresentado no INDUSCON 2025.

##  Resultados Principais

- **Melhor modelo**: Random Forest + SMOTE Tomek  
- **F1-score**: 82,3%
- **Precisão**: 84,4%
- **Recall**: 80,3%
- **AUC-ROC**: 93,5%

##  Como Usar

### Instalar dependências:
```bash
!pip install numpy==1.24.4
!pip install scikit-learn==1.4.2
!pip install imbalanced-learn==0.11.0 lime==0.2.0.1 xgboost==1.7.6
```

### Executar o notebook:
```bash
jupyter notebook code.ipynb
```

##  Arquivos

- `Codigo.ipynb` - **Notebook principal com todo o código**
- `requirements.txt` - Bibliotecas necessárias
- `dataset.csv/` - Dataset utilizado
- `results/` - Figuras e resultados gerados

##  O que o Notebook Faz

1. **Carrega e limpa os dados** (4.424 estudantes do IPP Portugal)
2. **Aplica técnicas de balanceamento**: SMOTE, SMOTE Tomek, SMOTE ENN, Under-sampling
3. **Treina modelos**: Random Forest e XGBoost
4. **Avalia performance** com múltiplas métricas
5. **Gera explicações LIME** dos fatores de risco/proteção
6. **Cria todas as visualizações** do artigo

##  Principal Descoberta

O **desempenho acadêmico nos primeiros semestres** é o fator mais importante para predizer evasão escolar.




📧 **Contato**: juliocesar.alvarenga@hotmail.com
