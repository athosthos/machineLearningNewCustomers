Treinamento de Machine Learning para prever o score de novos clientes em um banco.

Bibliotecas utilizadas:
- pandas
- scikit-learn

Foi utilizada uma basse de cliente com aproximadamente 100 mil registros, em que foi utilizada a ferramenta train_test_split para treinar e testar os dados (foi utilizado 70% dos dados para treinamento).
Depois, foram testados dois tipos de modelos: RandomForestClassifier e KNeighborsClassifier.

Após testes, foi visto que o modelo que apresentou maior precisão foi o da árvore, tendo cerca de 82% de precisão.
