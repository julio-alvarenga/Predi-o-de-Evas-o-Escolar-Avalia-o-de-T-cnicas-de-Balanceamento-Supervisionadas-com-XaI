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
pip install -r requirements.txt
```

### Executar o notebook:
```bash
jupyter notebook student_dropout_prediction.ipynb
```

##  Arquivos

- `student_dropout_prediction.ipynb` - **Notebook principal com todo o código**
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
