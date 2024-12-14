# 📍 Introdução
O objetivo da IA Preditiva criada é prever a taxa de sucesso dos alunos PCDs da UFCG, para isso, foi utilizado regressão linear combinada para atingir os objetivos desejados.

# 🔎 Como utilizar
1. Primeiro será necessário atualizar a base de dados para a que será utilizada no momento da avaliação, para que o modelo possa ser treinado conforme os novos dados.
``` python
url = "https://raw.githubusercontent.com/PaqTcPB-Inclui-UFCG/dados/refs/heads/main/dados_estudantes.csv"
dados = pd.read_csv(url)
```

2. Com os dados treinados, será necessário adicionar o dataFrame ue se deseja prever:
``` python
pred = modelo.predict(test)
```
Em que test será substituído pela nova base de dados

3. Exibilição dos resultados:
``` python
print(pred)
```
