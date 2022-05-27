
## Лабораторная работа по курсу "Инструменты анализа данных".<br/>
### *Классификация в sklearn. Метрики классификации.* <br/>
Samara University <br/>
DAT-2022

## 3.[Классификация в sklearn.](https://github.com/Dark-MonkGI/Data_Analysis_Tools_SAMARA_UNIVERSITY/blob/main/3.%20%D0%9A%D0%BB%D0%B0%D1%81%D1%81%D0%B8%D1%84%D0%B8%D0%BA%D0%B0%D1%86%D0%B8%D1%8F%20%D0%B2%20sklearn.%20%D0%9C%D0%B5%D1%82%D1%80%D0%B8%D0%BA%D0%B8%20%D0%BA%D0%BB%D0%B0%D1%81%D1%81%D0%B8%D1%84%D0%B8%D0%BA%D0%B0%D1%86%D0%B8%D0%B8/DAT_6131-010402D_Griaznov_I_LW3.ipynb)
**Цель данной работы:** познакомиться с инструментами ***`Классификация в sklearn`*** — это прямой и простой способ начать применять новые знания, чтобы сделать концепции машинного обучения конкретными, реализуя их с помощью удобной, хорошо документированной и надежной библиотеки.

> Scikit-Learn упрощает процесс создания классификатора и помогает более чётко выделить концепции машинного обучения, реализуя их с помощью понятной, хорошо документированной и надёжной библиотекой.
> Scikit-Learn — это Python-библиотека, впервые разработанная David Cournapeau в 2007 году. В этой библиотеке находится большое количество алгоритмов для задач, связанных с классификацией и машинным обучением в целом.


**В работе использовались:**
1. [Data Set](https://www.kaggle.com/datasets/iabhishekofficial/mobile-price-classification?select=test.csv): ***`Mobile Price Classification`***  <br/>
2. [Data Set](https://www.kaggle.com/datasets/nareshbhat/wine-quality-binary-classification): ***`Wine Quality Classification`***  <br/>

## Mobile Price Classification
**About Dataset** <br/>
Context <br/>

Боб основал свою собственную мобильную компанию. Он хочет дать жесткий бой крупным компаниям, таким как Apple, Samsung и т. д.<br/>

Он не знает, как оценить стоимость мобильных телефонов, которые производит его компания. <br/> На этом конкурентном рынке мобильных телефонов вы не можете просто предполагать. Для решения этой проблемы он собирает данные о продажах мобильных телефонов различных компаний.<br/>

Боб хочет выяснить какую-то связь между характеристиками мобильного телефона (например: оперативная память, внутренняя память и т. д.) и его продажной ценой.<br/>  Но он не так хорош в машинном обучении. Поэтому ему нужна ваша помощь, чтобы решить эту проблему.<br/>

В этой задаче вам не нужно предсказывать фактическую цену, а нужно предсказать диапазон цен, указывающий, насколько высока цена. <br/>


![logo](https://github.com/Dark-MonkGI/Data_Analysis_Tools_SAMARA_UNIVERSITY/blob/main/3.%20%D0%9A%D0%BB%D0%B0%D1%81%D1%81%D0%B8%D1%84%D0%B8%D0%BA%D0%B0%D1%86%D0%B8%D1%8F%20%D0%B2%20sklearn.%20%D0%9C%D0%B5%D1%82%D1%80%D0%B8%D0%BA%D0%B8%20%D0%BA%D0%BB%D0%B0%D1%81%D1%81%D0%B8%D1%84%D0%B8%D0%BA%D0%B0%D1%86%D0%B8%D0%B8/dataset-cover1.jpg)

## Wine Quality Classification
Data set for Binary Classification<br/>
<br/>
**About Dataset**<br/>

This Data set contains the information related red wine , Various factors affecting the quality. This data set was prepossessed and downloaded from the UCI Machine Learning Repository. This data set was simple, cleaned, practice data set for classification modelling. Source of this [Data Set](https://archive.ics.uci.edu/ml/datasets/wine+quality) <br/>

Attribute Information:<br/>
Input variables (based on physicochemical tests):<br/>
1 - fixed acidity<br/>
2 - volatile acidity<br/>
3 - citric acid<br/>
4 - residual sugar<br/>
5 - chlorides<br/>
6 - free sulfur dioxide<br/>
7 - total sulfur dioxide<br/>
8 - density<br/>
9 - pH<br/>
10 - sulphates<br/>
11 - alcohol<br/>
Output variable (based on sensory data):<br/>
12 - quality ('good' and 'bad' based on score >5 and <5)<br/>


![logo](https://github.com/Dark-MonkGI/Data_Analysis_Tools_SAMARA_UNIVERSITY/blob/main/3.%20%D0%9A%D0%BB%D0%B0%D1%81%D1%81%D0%B8%D1%84%D0%B8%D0%BA%D0%B0%D1%86%D0%B8%D1%8F%20%D0%B2%20sklearn.%20%D0%9C%D0%B5%D1%82%D1%80%D0%B8%D0%BA%D0%B8%20%D0%BA%D0%BB%D0%B0%D1%81%D1%81%D0%B8%D1%84%D0%B8%D0%BA%D0%B0%D1%86%D0%B8%D0%B8/dataset-cover.jpg)
