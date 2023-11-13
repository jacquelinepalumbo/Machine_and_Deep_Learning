# Machine and Deep Learning Projects

<h1>
    <a href="https://www.dio.me/">
     <img align="center" width="80px" src="https://chisellabs.com/blog/wp-content/uploads/2021/07/Minimum-Viable-Product-MVP.jpg"></a>
    <span> Minimum Viable Product</span>
</h1>

Nestes dois notebooks, os objetivos foram, repectivamente, trabalharmos com modelos de machine learning e criarmos um modelo de visão computacional. 

**Módulos - Machine and Deep Learning** do Projeto de Pós Gradução em Ciência de Dados e Analytics da Puc Rio  [Pós-Graduação em Ciência de Dados e Analytics](https://especializacao.ccec.puc-rio.br/especializacao/ciencia-de-dados-e-analytics).



1. 🔍 [Objetivo](#objetivo)
2. 🔨 [Ferramentas Utilizadas](#versions)  
3. 🚀 [1. Percurso Machine Learning](#percurso)
4. 🎆 [2. Percurso Deep Learning](#percurso-dl)
5. ☑️ [Análise Machine Learning](#analysis)
6. 📈 [Análise Deep Learning](#analysis-data)
7. 💬 [Contribuições](#contributors)    
8. 🔗 [Link](#link)  






## <a name="objetivo">🔍 Objetivos </a> 

1. Machine Learning: trataremos de um modelo em aprendizado supervisionado,para escolher o melhor modelo para prever o grau de obesidade.

2. Deep Learning: criar um modelo de visão computacional que consiga classificar as imagens em alguma das categorias de animais:pinguins e tartarugas.



## <a name="percurso">🚀 1. Percurso Machine Learning </a>

|      N°          |    Etapas        |
| ---------------- | -----------------|
|  1  | Coleta de dados               |
|  2  | Análise Exploratória          |
|  3  | Tratamento de Dados           |
|  4  | Machine Learning              |
|  5  | Pipelines                     |
|  6  | Otimização dos hiperparâmetros|
|  7  | Simulação em dados não vistos |

---

## <a name="percurso-dl">🎆 2. Percurso Deep Learning </a>

|      N°          |    Etapas        |
| ---------------- | -----------------|
|  1  | Coleta de dados               |
|  2  | Análise Exploratória          |
|  3  | Tratamento de Dados           |
|  4  | Machine Learning              |
|  5  | Rede Neural Convolucional     |
|  6  | Treinamento do modelo         |
|  7  | Simulação em dados não vistos |


## <a name="versions">🔨 Ferramentas Utilizadas </a>

- [Kaggle](https://azure.microsoft.com/pt-br/get-started/azure-portal)
    * Coleta de Dados
    
  
- [Google Colab:](https://colab.research.google.com/?utm_source=scs-index)
     ```bash
    # Importação das Bibliotecas:
    import numpy as np # Importação do Numpy
    import pandas as pd # Importação do Pandas
    import matplotlib.pyplot as plt # Importação do Matplotlib
    import seaborn as sns # importando a biblioteca Seaborn
    import tensorflow as tf # importando keras no Tensorflow
    from sklearn.model_selection import train_test_split # para particionar em bases de treino e teste (holdout)
    from sklearn.pipeline import Pipeline # para preparar os pipelines # para preparar os pipelines
    from sklearn.model_selection import KFold # para preparar os folds da validação cruzada
    from sklearn.model_selection import StratifiedKFold # para preparar os folds da validação estratificada
    from sklearn.model_selection import cross_val_score # para executar a validação cruzada
    from sklearn.metrics import accuracy_score # para a exibição da acurácia do modelo
    from sklearn.metrics import confusion_matrix # para a exibição da matriz de confusão
    ```

## <a name="analysis">☑️ Análise Machine Learning</a>

O dataset utilizado neste notebook possibilitará trabalharmos com modelos de machine learning (aprendizado de máquina), para escolher o melhor modelo para prever o grau de obesidade. Nossos dados são estruturados, onde foram extraídos de um banco de dados da plataforma Kaggle. Trataremos um modelo em aprendizado supervisionado, já que este modelo é construído a partir de um dataset, que são apresentados para um algoritmo na forma de entrada e saída desejada.

Resultado: Utilizando a validação cruzada estratificada para que o modelo treinado, resulte em melhor aproveitamento do dataset. Resultou em: a Árvore de Classificação CART com os dados padronizados e normalizados apresentaram a melhor acurácia, comparado aos dados orgininais.

Avaliação do modelo de Machine Learning: a acurácia do modelo nos dados de teste 0.99.

## <a name="analysis-data">📈 Análise Deep Learning</a>

Classificador de imagens binária - Pinguins VS Tartarugas.

Sobre o conjunto de dados 572 imagens únicas, divididas em uma pasta de treinamento de 500 imagens e uma pasta de validação de 72 imagens. O conjunto de dados é dividido 50:50 entre imagens de tartarugas e pinguins. Cada imagem contém exatamente uma instância de um objeto. 

Avaliação do modelo de deep learning: a acurácia do modelo nos dados de teste 82%.

Nosso modelo de treino e validação não apresentaram precisão e perdas fidedignas. Modelo deveria melhorar seus hiperparâmetros para melhor performance.

 ## <a name="contributors"> 💬 Contribuições</a>

 Este é um projeto feito para a comunidade, então sinta-se livre para contribuir.
 
 Além disso, você também pode contribuir:
 
⚠️ Ajudando, respondendo ou compartilhando o seu trabalho comigo! 

⭐ Adicionando aos favoritos! 




## <a name="link">🔗 Link</a>


[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jacqueline-ribeiro-743876247/)
---


<div align="center">Feito com muita dedicação por ❤️ <a href="https://github.com/jacquelinepalumbo">Jacqueline</a>.</div>
