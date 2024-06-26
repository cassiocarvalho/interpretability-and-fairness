# Interpretabilidade e Justiça Algorítmica: Avançando na Transparência de Modelos Preditivos de Evasão Escolar

## Estrutura do repositório

```bash
.
├── dropout
│   ├── counts                                                  # Número de amostras em cada conjunto
│   │   ├── y_counts.txt
│   │   ├── y_test2_counts.txt
│   │   ├── y_test_counts.txt
│   │   ├── y_train_counts.txt
│   │   └── y_train_smote_counts.txt
│   ├── dataset-early-2014-2017-v2_ProfileReport_Complete.html  # Análise exploratória
│   ├── dataset-early-2014-2017-v2_ProfileReport_Minimal.html   # Análise exploratória (Completa)
│   ├── dropout-Analysis.pdf                                    # Análise dos resultados
│   ├── dropout-runsANN.pdf                                     # Execuções ANN
│   ├── dropout-runsRandomForest.pdf                            # Execuções RandomForest
│   ├── dropout-runsXGBoost.pdf                                 # Execuções XGBoost
│   ├── exit_semester                                           # Número de amostras com base no semestre de saída
│   │   └── exit_semester_dataset.png                           
│   └── techniques                                              # Resultados modelos, clusterização de explicações LIME e justiça algorítmica
│       ├── ANN1
│       ├── ANN2
│       ├── ANN3
│       ├── ANN4
│       ├── ANN5
│       ├── ANN6
│       ├── ANN7
│       ├── ANN8
│       ├── ANN9
│       ├── ANN10
│       ├── radar
│       ├── RandomForest1
│       ├── RandomForest2
│       ├── RandomForest3
│       ├── RandomForest4
│       ├── RandomForest5
│       ├── RandomForest6
│       ├── RandomForest7
│       ├── RandomForest8
│       ├── RandomForest9
│       ├── RandomForest10
│       ├── XGBoost1
│       ├── XGBoost2
│       ├── XGBoost3
│       ├── XGBoost4
│       ├── XGBoost5
│       ├── XGBoost6
│       ├── XGBoost7
│       ├── XGBoost8
│       └── XGBoost9
│       ├── XGBoost10
└── README.md
