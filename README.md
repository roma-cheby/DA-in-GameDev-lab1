# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev]
Отчет по лабораторной работе #1 выполнил(а):
- Ахидов Роман Игоревич
- РИ210934
Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | 60 |
| Задание 2 | * | 20 |
| Задание 3 | * | 20 |

знак "*" - задание выполнено; знак "#" - задание не выполнено;

Работу проверили:
- к.т.н., доцент Денисов Д.В.
- к.э.н., доцент Панов М.А.
- ст. преп., Фадеев В.О.

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

## Цель работы
Ознакомиться с основными операторами зыка Python на примере реализации линейной регрессии.

## Задание 1.
### print("Hello World")
- ![image](https://user-images.githubusercontent.com/105049918/190560776-c9665a2c-0139-4409-b601-c905b8083e60.png)
- ![image](https://user-images.githubusercontent.com/105049918/190560830-f0ece4f9-8eb3-40ba-b266-42dce8a9f217.png)
- ![image](https://user-images.githubusercontent.com/105049918/190561685-5d7f6187-ceb6-495b-8c72-8f56600c6080.png)



## Задание 2.
### Пошагово выполнить каждый пункт раздела "ход работы" с описанием и примерами реализации задач
Ход работы:
- Произвести подготовку данных для работы с алгоритмом линейной регрессии. 10 видов данных были установлены случайным образом, и данные находились в линейной зависимости. Данные преобразуются в формат массива, чтобы их можно было вычислить напрямую при использовании умножения и сложения.

- Определите связанные функции. Функция модели: определяет модель линейной регрессии wx+b. Функция потерь: функция потерь среднеквадратичной ошибки. Функция оптимизации: метод градиентного спуска для нахождения частных производных w и b.

![image](https://user-images.githubusercontent.com/105049918/190895477-b4f5d226-9f0d-4946-8086-b355c997776e.png)

Код задания можно посмотреть по ссылке: https://colab.research.google.com/drive/19aCJRYgkoxyFEQIqXTeDHqc-FbwNYwGW?usp=sharing

Связанными являются функции: model - loss_function, model - optimize, iterate - optimize, iterate - model; (одна из пары используется в другой)

## Задание 3
### Должна ли величина loss стремиться к нулю при изменении исходных данных? Ответьте на вопрос, приведите пример выполнения кода, который подтверждает ваш ответ.
![image](https://user-images.githubusercontent.com/105049918/190895470-fee6adae-50b6-4df4-8739-535c681ede3a.png)
При увеличении значений a или b значение функции loss_function имеет тенденцию увеличения.

### Какова роль параметра Lr? Ответьте на вопрос, приведите пример выполнения кода, который подтверждает ваш ответ. В качестве эксперимента можете изменить значение параметра.
![image](https://user-images.githubusercontent.com/105049918/190895556-54771d71-b5f9-4bb2-a774-a6f00ec95b22.png)
![image](https://user-images.githubusercontent.com/105049918/190895583-fa4c1a5b-0b7e-49d8-9d3e-3afe67acd1e8.png)
![image](https://user-images.githubusercontent.com/105049918/190895649-6d6ab27e-977c-45e7-b581-066acaec27cc.png)
При увеличении Lr увеличивается расфокусировка лучей. Значит Lr влияет на это.

## Выводы

Я поработал в Google Colab в первый раз, узнал что такоеп связанные функции, определил их. Установил Unity и Anaconda, но почти ничего не узнал про numpy/pandas, не до конца разобрался с Unity.

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Powered by

**BigDigital Team: Denisov | Fadeev | Panov**
