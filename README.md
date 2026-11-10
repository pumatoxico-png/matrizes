# 🐍 Matrizes em Python

> Exercício de Python sobre criação, acesso e iteração em matrizes utilizando listas aninhadas.

## 🎯 Objetivo
Compreender como organizar dados em linhas e colunas, acessar elementos por índices e percorrer registros de uma matriz.

## 📚 Conceitos utilizados
- Matrizes
- Listas aninhadas
- Índices de linha e coluna (`[linha][coluna]`)
- Laço de repetição (`for`)
- Desempacotamento de elementos

## ⚙️ Código

```python
tabela = [
    ['T01', 25.0, 63],
    ['T02', 26.5, 58],
]

tabela[1][0]
tabela[1][1]

for sensor, temp, umid in tabela:
    print(sensor, temp, umid)
```

## 📊 Funcionamento
1. Cria uma matriz com dois registros de sensores.
2. Cada linha contém identificação, temperatura e umidade.
3. Acessa elementos específicos utilizando índices.
4. Percorre as linhas com `for`.
5. Separa os valores de cada linha em variáveis.

## 💻 Exemplo de execução

```text
T01 25.0 63
T02 26.5 58
```

## 🧠 Aprendizado
Compreensão da organização de dados em matrizes, utilização de índices para acessar linhas e colunas e iteração sobre seus elementos.
