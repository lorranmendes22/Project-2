##Project 2

Este projeto visa prever se projetos serão concluídos ou não com base em atributos como horas esperadas e preço estimado. Utilizamos diferentes modelos de machine learning para realizar essa classificação.

## Descrição dos Arquivos

- **projeto_classificacao.py**: Script principal que carrega os dados, treina os modelos, realiza previsões e avalia a acurácia.
- **projects.csv**: Conjunto de dados utilizado, contendo informações sobre projetos e seu status de conclusão.

## Pré-requisitos

Certifique-se de ter Python 3.x instalado junto com os seguintes pacotes:

- pandas
- scikit-learn
- seaborn
- matplotlib

Instale os pacotes necessários usando o comando:

```
pip install pandas scikit-learn seaborn matplotlib
```

## Executando o Projeto

1. Clone o repositório:

```
git clone https://github.com/seu-usuario/projeto-classificacao.git
cd projeto-classificacao
```

2. Execute o script principal:

```
python projeto_classificacao.py
```

## Modelos Utilizados

Os seguintes modelos foram testados para classificação:

- Support Vector Machine (SVM)
- Dummy Classifier (para comparação)

## Resultados

Após treinamento e teste dos modelos, obtivemos os seguintes resultados:

- SVM:
  - Acurácia: 67.22%

- Dummy Classifier (stratified):
  - Acurácia: 52.59%

## Visualizações

Incluímos gráficos para visualizar a distribuição dos dados e a fronteira de decisão dos modelos.

- Scatterplot dos dados de teste com cores indicando o status de conclusão dos projetos.
- Contour plot mostrando a fronteira de decisão do modelo SVM.

## Conclusão

Este projeto demonstra como utilizar machine learning para prever a conclusão de projetos com base em atributos iniciais. A escolha e o pré-processamento dos dados são fundamentais para melhorar a acurácia dos modelos.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests para melhorar este projeto.

