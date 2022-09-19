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
    
    ![DataTable.png](Imagens/1_Entendimento_dos_dados/1_DataTable.png)
    

 

### Dados estatísticos

![FeatureStatistics.png](Imagens/1_Entendimento_dos_dados/3_FeatureStatistics.png)

- **Idade**
    
    Mínima***:*** 16 anos;
    
    Média/Mediana: 40 anos;
    
    Máxima: 110 Anos.
    

![DistributionsAge.png](Imagens/1_Entendimento_dos_dados/5_DistributionsAge.png)

- **Salário anual**
    
    Mínima: 100;
    
    Média: 72 693;
    
    Mediana: 72 000;
    
    Máxima: 152 500.
    

![DistributionsSalary.png](Imagens/1_Entendimento_dos_dados/6_DistributionsSalary.png)

- **Gênero**
    
    Compra feminino: 220;
    
    Não compra feminino: 297;
    
    Compra Masculino:184;
    
    Não compra masculino: 302.
    

![MosaicDisplay.png](Imagens/1_Entendimento_dos_dados/4_MosaicDisplay.png)

## 3. **Preparação dos dados**

1. Excluindo coluna User ID:
    
    ![ExcluindoColuna.png](Imagens/2_Preparação_dos_dados/1_ExcluindoColuna.png)
    
2. Substituindo feminino por 0 e masculino por 1:
    
    ![SubstituindoFemale.png](Imagens/2_Preparação_dos_dados/2_SubstituindoFemale.png)
    
    ![SubstituindoMale.png](Imagens/2_Preparação_dos_dados/3_SubstituindoMale.png)
    
3. Detectando e deletando dados enviesados:
    
    ![LocalizandoDadosDefeitos.png](Imagens/2_Preparação_dos_dados/4_LocalizandoDadosDefeitos.png)
    
    ![ExcluindoDadosDefeitos.png](Imagens/2_Preparação_dos_dados/5_ExcluindoDadosDefeitos.png)
    

## 2.1 **Entendimento dos dados**

![DataTableLimpo.png](Imagens/3_Modelagem/1_DataTableLimpo.png)

## 4. **Modelagem**

![Modelagem.png](Imagens/3_Modelagem/2_Modelagem.png)

Métodos selecionados:

- Árvore;
- Rede neural.

## 5. **Avaliação do modelo**

Gerando dados para treino dos modelos:

![DataSampleTeste.png](Imagens/4_Avaliação do modelo/1_DataSampleTeste.png)

Removida coluna purchased dos dados de teste:

![SelectColumnsTest.png](Imagens/4_Avaliação do modelo/2_SelectColumnsTest.png)

Tabela com os dados para treino:

![DataTableTest.png](Imagens/4_Avaliação do modelo/3_DataTableTest.png)

Resultado final do teste dos modelos, temos:

![PredictionsTest.png](Imagens/4_Avaliação do modelo/4_PredictionsTest.png)

## 6. **Publicação**

![qrcode_github.com.png](Imagens/qrcode_github.com.png)

***Link***: [***thiagopereiramagalhaes/Data-Mining-com-CRISP-DM (github.com)***](https://github.com/thiagopereiramagalhaes/Data-Mining-com-CRISP-DM)
