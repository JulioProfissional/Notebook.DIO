Estrutura do README.md
1. Objetivo

Explicar o problema de fraude em cartão de crédito e o forte desbalanceamento.

2. Preparação dos Dados
Leitura via URL
Log do Amount
Padronização
Split estratificado
3. Modelos Testados
Modelo	Recall	Precision	F1
Logistic Regression	...	...	...
Random Forest	...	...	...
XGBoost	...	...	...
4. Ajuste de Limiar

Explicar o impacto do threshold 0.3.

5. Interpretabilidade
Importância das features
SHAP
6. Conclusão

Explicar qual modelo apresentou melhor equilíbrio entre Recall, Precisão e F1 para a classe fraude.

Dica importante para ganhar pontos

Não destaque a acurácia como principal métrica. Mostre explicitamente algo como:

"Uma acurácia superior a 99% não significa que o modelo é eficiente, pois apenas 0,17% das observações representam fraude. Por isso, a avaliação foi baseada principalmente em Recall, Precisão e F1-score da classe fraudulenta."

Isso demonstra exatamente o entendimento que a DIO quer verificar nesse desafio.
# Notebook.DIO
