# Projeto de Análise de Imóveis

Este projeto realiza a análise de dados de imóveis utilizando a biblioteca pandas do Python. O objetivo é manipular e analisar um conjunto de dados que contém informações sobre diferentes tipos de imóveis, como apartamentos, casas, quitinetes, entre outros.

## Estrutura do Projeto

- `Numpy.ipynb`: Notebook Jupyter contendo o código para carregar, manipular e analisar os dados dos imóveis.
- `apples_ts.csv`: Arquivo CSV contendo os dados dos imóveis.

## Dependências

Para executar este projeto, você precisará das seguintes bibliotecas Python:

- pandas
- numpy

Você pode instalar essas dependências usando o pip:

```sh
pip install pandas numpy
```

Uso
1 - Clone este repositório para o seu ambiente local:

git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio

2 - Certifique-se de que o arquivo apples_ts.csv está no diretório correto.

3 - Abra o notebook Numpy.ipynb em um ambiente Jupyter Notebook ou JupyterLab.

4 - Execute as células do notebook para carregar e analisar os dados dos imóveis.

Exemplo de Código
Aqui está um exemplo de como carregar e manipular os dados dos imóveis:

```python
import pandas as pd

# Carregar os dados do arquivo CSV
df = pd.read_csv('apples_ts.csv')

# Exibir as primeiras linhas do DataFrame
print(df.head())

# Remover a coluna 'Descricao'
df = df.drop(columns=['Descricao'])

# Exibir o DataFrame resultante
print(df)
```

Contribuição
Se você quiser contribuir para este projeto, sinta-se à vontade para abrir uma issue ou enviar um pull request.

Licença
Este projeto está licenciado sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.
