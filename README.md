# Data Mining com CRISP-DM

## 1. **Entendimento do negócio**

### ****Carros - Conjunto de Dados de Decisão de Compra****

Este conjunto de dados contém detalhes de 1000 clientes, indicando se um cliente comprou ou não um carro.

**Fonte:** [Carros - Dataset de decisão de compra | Kaggle](https://www.kaggle.com/datasets/gabrielsantello/cars-purchase-decision-dataset)

## 2. **Entendimento dos dados**

- **Colunas**
    1. Purchased(Comprado) - Categórico;
    2. User ID - Numérico;
    3. Gender(Gênero) - Categórico;
    4. Age(Idade) - Numérico;
    5. AnnualSalary(Salário anual) - Numérico.
- **Linhas:** 1003.
    
    ![DataTable.png](Data%20Mining%20com%20CRISP-DM%202a67c23706994f95aab7c574baed6990/DataTable.png)
    

 

### Dados estatísticos

![FeatureStatistics.png](Data%20Mining%20com%20CRISP-DM%202a67c23706994f95aab7c574baed6990/FeatureStatistics.png)

- **Idade**
    
    Mínima***:*** 16 anos;
    
    Média/Mediana: 40 anos;
    
    Máxima: 110 Anos.
    

![DistributionsAge.png](Data%20Mining%20com%20CRISP-DM%202a67c23706994f95aab7c574baed6990/DistributionsAge.png)

- **Salário anual**
    
    Mínima: 100;
    
    Média: 72 693;
    
    Mediana: 72 000;
    
    Máxima: 152 500.
    

![DistributionsSalary.png](Data%20Mining%20com%20CRISP-DM%202a67c23706994f95aab7c574baed6990/DistributionsSalary.png)

- **Gênero**
    
    Compra feminino: 220;
    
    Não compra feminino: 297;
    
    Compra Masculino:184;
    
    Não compra masculino: 302.
    

![MosaicDisplay.png](Data%20Mining%20com%20CRISP-DM%202a67c23706994f95aab7c574baed6990/MosaicDisplay.png)

## 3. **Preparação dos dados**

1. Excluindo coluna User ID:
    
    ![ExcluindoColuna.png](Data%20Mining%20com%20CRISP-DM%202a67c23706994f95aab7c574baed6990/ExcluindoColuna.png)
    
2. Substituindo feminino por 0 e masculino por 1:
    
    ![SubstituindoFemale.png](Data%20Mining%20com%20CRISP-DM%202a67c23706994f95aab7c574baed6990/SubstituindoFemale.png)
    
    ![SubstituindoMale.png](Data%20Mining%20com%20CRISP-DM%202a67c23706994f95aab7c574baed6990/SubstituindoMale.png)
    
3. Detectando e deletando dados enviesados:
    
    ![LocalizandoDadosDefeitos.png](Data%20Mining%20com%20CRISP-DM%202a67c23706994f95aab7c574baed6990/LocalizandoDadosDefeitos.png)
    
    ![ExcluindoDadosDefeitos.png](Data%20Mining%20com%20CRISP-DM%202a67c23706994f95aab7c574baed6990/ExcluindoDadosDefeitos.png)
    

## 2.1 **Entendimento dos dados**

![DataTableLimpo.png](Data%20Mining%20com%20CRISP-DM%202a67c23706994f95aab7c574baed6990/DataTableLimpo.png)

## 4. **Modelagem**

![Modelagem.png](Data%20Mining%20com%20CRISP-DM%202a67c23706994f95aab7c574baed6990/Modelagem.png)

Métodos selecionados:

- Árvore;
- Rede neural.

## 5. **Avaliação do modelo**

Gerando dados para treino dos modelos:

![DataSampleTeste.png](Data%20Mining%20com%20CRISP-DM%202a67c23706994f95aab7c574baed6990/DataSampleTeste.png)

Removida coluna purchased dos dados de teste:

![SelectColumnsTest.png](Data%20Mining%20com%20CRISP-DM%202a67c23706994f95aab7c574baed6990/SelectColumnsTest.png)

Tabela com os dados para treino:

![DataTableTest.png](Data%20Mining%20com%20CRISP-DM%202a67c23706994f95aab7c574baed6990/DataTableTest.png)

Resultado final do teste dos modelos, temos:

![PredictionsTest.png](Data%20Mining%20com%20CRISP-DM%202a67c23706994f95aab7c574baed6990/PredictionsTest.png)

## 6. **Publicação**

![qrcode_github.com.png](Data%20Mining%20com%20CRISP-DM%202a67c23706994f95aab7c574baed6990/qrcode_github.com.png)

***Link***: [***thiagopereiramagalhaes/Data-Mining-com-CRISP-DM (github.com)***](https://github.com/thiagopereiramagalhaes/Data-Mining-com-CRISP-DM)
