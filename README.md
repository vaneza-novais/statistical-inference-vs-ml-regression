## Previsão de custos de seguros de saúde
Esse projeto tem como objetivo investigar como fatores demográficos, sociais e hábitos influenciam nos custos de um seguro de saúde utilizando **Modelagem Estatistica e Machine Learning**.  
O trabalho se encontra dividido em 3 etapas:  
* Análise e diagnostico dos dados: compreensão dos dados, verificação de outliers e correlações  
* Regressão Estatistíca: Aplicação de OLS para verificar e validar a relevância das variáveis e entender a linearidade dos dados através do resíduos
* Machine Learning: Comparação entre modelos lineares e não linerares, cross validation, teste de validade e feature importance
### **Conclusões:**  
O hábito de fumar junto a um elevado IMC, para os dados analisados, é o principal fator para aumento do custo do seguro, superando variáveis como idade e região.  
O modelo com melhor desempenho foi o Random Forest com um R² de 0.88 e MAE de 2500 unidades, além disso apresentou alta estabilidade com testes aleatórios no random_state.  

### **Tecnologias Utilizadas**
* Python (Pandas, NumPy, Matplotlib, Seaborn)
* Statsmodels (Regressão Estatística e Testes de Hipótese)
* Scikit-Learn (Machine Learning, Métricas e Validação)
