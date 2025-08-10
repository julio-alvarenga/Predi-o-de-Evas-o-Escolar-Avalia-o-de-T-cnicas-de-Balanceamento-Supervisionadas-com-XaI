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

### Executar:
```bash
python main.py
```

##  O que tem aqui

- `main.py` - Script principal que executa todos os experimentos
- `data_preprocessing.py` - Limpeza e preparação dos dados
- `models.py` - Random Forest e XGBoost com técnicas de balanceamento
- `lime_analysis.py` - Análise de explicabilidade
- `requirements.txt` - Bibliotecas necessárias

##  Sobre o Estudo

Utilizamos dados de 4.424 estudantes do Instituto Politécnico de Portalegre (Portugal) para comparar diferentes técnicas de balanceamento:

- SMOTE
- SMOTE + Tomek Links  
- SMOTE + ENN
- Under-sampling

**Principal descoberta**: Desempenho acadêmico nos primeiros semestres é o fator mais importante para predizer evasão.

##  Autores

**Julio Cesar Nunes Alvarenga** & **Cassius Zanetti Resende**  
Instituto Federal do Espírito Santo (IFES)

## 📄 Como Citar

```bibtex

 **Contato**: juliocesar.alvarenga@hotmail.com
