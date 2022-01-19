## Neural-network

# 1

**Создание простейшей нейронной сети с помощью библиотеки Keras.**

Создание простой нейронной сети (библиотека Keras), активационные функции.

 Функции ошибок (loss functions), оптимайзеры, градиентный спуск.

 Распознание рукописной цифры на основе базы рукописных цифр MNIST (60000 рукописных цифр).

# 2

**Полносвязные сети, обучающая и тестовая выборки**

Оценка качества обучения нейросети. Почему недостаточно только функции ошибки для оценки нейросети. Что такое bias, для чего используется.

Результат урока.
Вы научитесь более грамотно оценивать нейросети.

Часть 1. Теоретическая часть
В видео рассматриваются: Описание bias. Что это такое, зачем он нужен. Описание модели что такое весовые параметры и откуда они берутся. Разделение данных на обучающую, проверочную и тестовую выборки и зачем они нужны на примере базы данных MNIST (60 000 вариантов написания рукописных цифр). Схема обучения нейронной сети. Что такое переобучение, как с ним бороться. Что такое Dropout и Normalization, для чего они нужны и как улучшают качество модели. 


# 3

**Свёрточные нейронные сети**


Цель урока.
Дать понятие что такое свёрточные нейронные сети, как они реализуются в библиотеке Keras. Повторить структуру свёрточных нейронных сетей. Ответить на вопросы: «Чем они лучше полносвязных (можно сказать стандартными) нейронных сетей? Почему свёрточные сети - лучший способ обработки изображений?». Отработать навык написания свёрточных нейронных сетей.

Результат урока.
Вы научитесь наиболее эффективному способу обработки изображения. Научитесь эффективно решать задачи компьютерного зрения.

Теоретическая часть.
В видео рассматриваются: Описание полносвязной и свёрточной нейронных сети. Что такое свёртка и как она применяется. 

# 4

**Обработка текстов с помощью нейросетей**

Цель урока.
Повторить принципы работы нейросетей. Научиться решать задачи обработки естественного языка с помощью нейронных сетей.

Результат урока.
Вы интуитивно будете понимать, как происходит обработка текстов с помощью нейросетей и сможете самостоятельно написать алгоритм для их обработки.

Теоретическая часть.
В видео рассматривается: Описание подходов, которые применяются при обработке текстов. Какие есть отличия от обработки изображений. Повторения принципов работы нейронных сетей. Объяснение что такое токенизация и Embedding и как это поможет при обработке естественного языка. Объяснение, что такое Bag of Words и для чего он нужен. 

# 5

**Рекуррентные нейронные сети и одномерные свёрточные сети для обработки текстов**

Цель урока.
Научиться обрабатывать текста на естественном языке, учитывая контекст. Понять принцип работы рекуррентных нейронных сетей, и чем он лучше стандартных подходов (Bag of Words/Embedding). Повторение измерения размерностей.

Результат урока.
Вы научитесь самостоятельно обрабатывать тексты, учитывая место слова в предложении, а значит и контекст.

Теоретическая часть.
В видео рассматриваются: описание и принцип работы рекуррентного слоя библиотеки Keras. Проблема исчезающего градиента и как она решается. Использование слоя LSTM. Повторение измерения размерностей. Описание двунаправленных нейронных сетей. Знакомство со слоями, которые реализованы в библиотеке Keras (SimpleRNN, GRU, LSTM). Принцип работы одномерной свертки.

# 6

**Нейронные сети для решения задачи регрессии**

Цель урока.
Знакомство с новым методом моделированием как регрессия.

Результат урока.
Вы научитесь писать архитектуры нейронных сетей для получения прогноза в задаче регрессии.

В видео рассматривается: Применение функционального программирования к построению нейронных сетей. Парсинг и нормировка полученных данных. Прогноз зарплат на базе данных сайта HeadHunter. Применение построенной модели для оценки стоимости квартир.

# 7

**Полносвязные и рекуррентные нейронные сети для прогнозирования временных рядов**

Цель урока.
Вы поймете отличия данных временных рядов от других данных для задачи регрессии.

Результат урока.
Вы научитесь правильно создавать выборки для подачи в модель. Узнаете, какие архитектуры сетей можно использовать для прогноза временных рядов.

В видео рассматриваются: Какие есть примеры данных временных рядов, в чем их отличия и особенности. Какие используются нормировки для таких данных. Что такое автокорреляция. Будет разобран пример прогнозирования акций лукойла - одна из основных задач временных рядов.

# 8

**Прямые и свёрточные нейронные сети для обработки аудиосигналов**

Описание занятия
Цель урока.
Вы придете к пониманию, что такое звук. Какие признаки можно извлечь из звука, чтобы подать их модель. Узнаете, как визуализировать аудио сигнал.

Результат урока.
Вы научитесь извлекать полезные признаки из аудио. Строить модели, на вход которой будут приходить параметры аудио.

В видео рассматриваются: В первом ноутбуке происходит визуализация, обработка аудио сигнала и извлечение признаков с помощью библиотеки librosa. Во втором мы строим нейронную сеть для классификации жанров музыки.

Место в курсе.
Изучение этого компонента поможет Вам обрабатывать аудио и писать архитектуру нейронных сетей для звуков.

Необходимые материалы:

Презентация https://docs.google.com/presentation/d/1RY2wPLIoocd0ZsPQspSrLCkqH_7qMwG6T4yceI0mvqY/edit?usp=sharing

Методичка https://drive.google.com/file/d/1R_sHhrk42tOF3R3VxQpmRQGKgVwnxdg0/view?usp=sharing

Ноутбук-практикум № 1 https://colab.research.google.com/drive/1mcB6OmfvU01hAIMbxtUMM-oQvw3FwTuS?usp=sharing

Ноутбук-практики № 2 https://colab.research.google.com/drive/1yVk7vqFs5I8TzIjEP4m40UB5_PNEICse?usp=sharing 
 
База для параметризации https://drive.google.com/open?id=1_NgkU1I_5Aar59qZjJVl2D-Gzjd7-aBQ

База для аудио GENRES.ZIP https://drive.google.com/open?id=1XsFcjb8aR7RYzHbCZqTrhv7tBTn--ySq


# 9

**Автокодировщики**

Описание занятия
Цель урока.
Вы изучите тему автокодировщик, как и где их применять и для чего они нужны. Познакомитесь с новой архитектурой нейронных сетей.

Результат урока.
Вы сможете написать свою модель автокодировщика. С его помощью искать выбросы, удалять с картинок шумы, и генерировать новые данные.

В видео рассматриваются: Первая практическая задача - обучить модель сжимать картинку с цифрой mnist в латентное (embedding) пространство, а затем обратно разворачивать в картинку с минимум потерь в сравнении с оригинальной. 
Вторая задача - восстановить лицо из зашумленной картинки. Третья задача - определить мошеннические операции.

Место в курсе.
Понимание этой темы поможет разобраться в вариационных автокодировщиках и познать проблемы простых автокодировщиков.

Необходимые материалы:

Презентация https://docs.google.com/presentation/d/1TCJr0yfYhfF0zcwMn3l0HYIKSe0o39FSZZjlTOLq8aU/edit?usp=sharing

Методичка https://drive.google.com/file/d/1NoOuHKyD_iSHMCYOAJfv8Tiv-cWgF7BO/view?usp=sharing

Ноутбук-практикум https://colab.research.google.com/drive/1ndRtdEjB2KCJ-HFywncjzmUtdw4LkLxm?usp=sharing 

База CREDITCARD https://storage.googleapis.com/datasets_ai/Bas%D0%B5Unit/12_autoencoder/creditcard.csv

База лиц https://storage.googleapis.com/datasets_ai/Bas%D0%B5Unit/12_autoencoder/facez.zip
 

*Если у Вас не получается открыть ноутбук или появляется уведомление об ошибке, попробуйте открыть ноутбук по данной ссылке:   https://colab.research.google.com/drive/14Q6akbmLQtSfuMaO1aJaCopWvU3QbO2u?usp=sharing 

# 10

**Вариационные автокодировщики, генеративные модели на базе автокодировщиков**

Описание занятия
Цель урока.
Вы разберетесь зачем нужны вариационные автокодировщики, какие проблемы они решают, и чем они отличаются от обычных автокодировщиков.

Результат урока.
Вы сможете изменить скрытое пространство полученное от автокодировщика так, чтобы модель смогла генерировать осмысленные картинки из шума.

Место в курсе.
Изучение данного урока поможет в дальнейшем для понимания таких тем как сегментации изображений, генеративно-состязательные сети и детекция объектов на изображении.

Необходимые материалы:

Презентация https://drive.google.com/file/d/1ysBMeaAv67WTCPP0LF4guHpZe3jtE_Ca/view?usp=sharing

Методичка https://drive.google.com/file/d/10G6jmMYOX65QU36vDGa_kB1QiBNgbX4Y/view?usp=sharing

Ноутбук-практикум https://drive.google.com/file/d/18migx5e9jvP5aKenGPjESKwx-lq7T2S9/view?usp=sharing
Дополнительный ноутбук  https://colab.research.google.com/drive/14Q6akbmLQtSfuMaO1aJaCopWvU3QbO2u?usp=sharing#scrollTo=6_fVoBT8HnvH

# 11

**Генеративные состязательные сети**

Описание занятия
Цель урока.
На этом уроке Вы познакомитесь с новой архитектурой: генеративно-состязательные сети. Как с их помощью можно из шума генерировать осмысленные картинки.

Результат урока.
Вы узнаете из чего состоит модель GAN, что такое генератор и дискриминатор, и какие функции они выполняют для создании новой информации.

В течение занятия напишем функции создания генератора и дискриминатора, научимся обучать такую архитектуру. Напишем ган на полносвязных слоях, протестируем его и сравним со сверточным. Узнаем, как поведет себя модель при сильном дискриминаторе и слабом генераторе и наоборот. Создадим новые данные на базе cifar10.
В домашнем задании необходимо будет генерировать новые картинки, на которых есть изображение самолета.

Место в курсе.
Для успешного изучения данного урока потребуются знания прошедших занятий, а именно: Вариационные автокодировщики.

Необходимые материалы:

Презентация https://docs.google.com/presentation/d/1y2571aPmHdvGj9hdMJBQQY_bUuOb7Cnhpaqj3KK2yFk/edit?usp=sharing

Методичка https://drive.google.com/file/d/1GdAU4P6QIEO7g5ucBDAlGaujWWEmGi77/view?usp=sharing

Ноутбук-практикум https://colab.research.google.com/drive/18YusOG9bcqFulzTuTHdR_bllxO83imrU?usp=sharing

База AIRPLANES https://drive.google.com/drive/folders/1Oq3rG1WhrJ0rQ_EvcmMCHVtIc-_7T4G0


# 12

**Введение в генетические алгоритмы**

Описание занятия
Цель урока.
Познакомить с общими понятиями генетического алгоритма и теорией эволюции, на основе которой строятся все генетические алгоритмы.

Результат урока.
Вы узнаете, что такое генетический алгоритм, какие задачи можно решить с его помощью. Получите практические навыки по решению задач с помощью генетического алгоритма.

Теоретическая часть.
В видео рассматривается: Что такое генетические алгоритмы? Что такое особи и популяция? Что такое генотип? Способ управления алгоритмом (оптимизируемая функция). Запуск естественного отбора. Что такое скрещивание и как с помощью него улучшить популяцию?

Место в курсе.
Генетический алгоритм, хотя и является частью машинного обучения, но для его изучения не нужно обладать никакими начальными навыками, кроме базового python (первых 3 урока будет достаточно). Этот урок необходимо пройти перед «Генетические алгоритмы для обучения нейронных сетей».

Необходимые материалы: 

Презентация https://docs.google.com/presentation/d/1YYgPJHRCt64ryS46l_qy8LOhlMzw2NQTSAhaAHHvUow/edit?usp=sharing

Методичка https://drive.google.com/file/d/1jaLv4Ofi8o0lZsmeYLddhkZd25KY00gS/view?usp=sharing

Ноутбук-практикум № 1 https://colab.research.google.com/drive/1S65ymF_iTfF438CJI8UfQ-b7_iWJVWS2?usp=sharing

Ноутбук-практикум №2 https://colab.research.google.com/drive/1BVPyCjoZ0iY__C0huTEvBP4-oOl4xN9Z?usp=sharing


# 13

**Генетические алгоритмы для обучения нейронных сетей**

Описание занятия
Цель урока.
Познакомить с принципом подбора гиперпараметров с помощью генетических алгоритмов.

Результат урока.
Вы научитесь самостоятельно решать наиболее сложную задачу в нейронных сетях - подбор гиперпараметров для нейросети.

В видео рассматриваются:
- Повторение генетических алгоритмов
- Описание общей идеи построения гиперпараметров с помощью генетического алгоритма
- Написание генетического алгоритма в контексте подбора гиперпараметров нейронной сети

Место в курсе.
Перед прохождением данного урока нужно понять принципы работы генетических алгоритмов. Урок «Введение в генетические алгоритмы». Данный урок будет полезен при любой настройке гиперпараметров, а значит практически в любой теме, которая касается написания нейронных сетей.

Необходимые материалы:

Методичка https://drive.google.com/file/d/1uizOYkzwINtLJwj9avj3YjzHAC8Knei8/view?usp=sharing

Ноутбук-практикум https://colab.research.google.com/drive/1UirxbPjPK7phgen9cUtfJk7mtf6wsFyD?usp=sharing
База. Трафик сайта. https://drive.google.com/open?id=1hU_-9dJ2qPDDGThIdwRkOKxmWgox92V3


# 14

**Сегментация изображений**

Описание занятия
Цель урока.
Это занятие поможет разобраться, что такое сегментация изображений. Какая используется архитектура. Как готовить датасет для подачи в модель.

Результат урока.
Вы ознакомитесь с плюсами и минусами разных архитектур для сегментации картинок, какие функции ошибок и метрики применяются в этой задаче.

На уроке Вы научитесь собирать данные для подачи в модель, визуализировать выборку с несколькими выделенными классами на картинке. Напишите разные варианты модели Unet (одна из архитектур для сегментации).
Создадите свою метрику для отслеживания результата тренировки сети. Попробуете сегментировать на классы изображения со стройки. А также попиксельно определите местонахождения самолета.

Место в курсе.
Вам пригодятся знания прошедших уроков: автокодировщики, сверточные сети, ГАНы. Понимание этой темы пригодится для изучения сегментации текста.

Необходимые материалы:

Презентация https://drive.google.com/file/d/1o9XiPdy5dqXYovWR9D1GU684Otefkybo/view?usp=sharing

Методичка https://drive.google.com/file/d/1rl4mt4Gvz3T3SUUYDVix2pQtqNDvMFgY/view?usp=sharing

Ноутбук-практикум https://colab.research.google.com/drive/1n1jVZWVKIm7lCf_oT753TZj32kGaL3dh

База сегментация https://drive.google.com/drive/folders/1dTjUj0MhtB70XIVw0di8riiv46ztRB6D?usp=sharing

База https://drive.google.com/drive/folders/1AvlQP7P5itQZkB9OgwtjVJWHLvekFgmf?usp=sharing

База движение по улицам https://drive.google.com/drive/folders/19KmO4Bzir520adBPPH2Dl5mooWF2tOuf?usp=sharing

База кожных заболеваний https://drive.google.com/drive/folders/1UJZdbqRo6UpViDIDKThSiXmfbtYO1Y9o?usp=sharing

# 15

**Алгоритмы кластеризации данных**

Цель урока.
Познакомить Вас с одной из задач классического машинного обучения - кластеризацией с помощью метода K-Means.

Результат урока.
Вы узнаете о том, что такое задача кластеризации и изучите метод K-Means (К-средних). И научитесь применять данный метод для решения практических задач.

Теоретическая часть.
В видео рассматривается: 
1. Что является задачей кластеризации.
2. Где применяется кластеризация
3. Что такое кластер?
4. Как анализировать кластеры
5. Метрика близости для кластера
6. Как выбрать количество кластеров (гиперпараметр)
7. Как работает метод K-Means

Место в курсе.
Задача кластеризации стоит немного «особняком», но её изучение расширит кругозор и спектр используемых методов для решения практических задач. К уроку можно приступать после изучения занятий по обработке текстов (использование Embedding).

Необходимые материалы:

Методичка https://drive.google.com/file/d/18DbfDhtlyaGyvOhqoE_OK2oSiUZbn0R1/view?usp=sharing

Презентация https://drive.google.com/file/d/1UqQvxau_5-yWxUdeo9aQXwnUj3MPm4kO/view?usp=sharing

Ноутбук https://colab.research.google.com/drive/115NiCoT-C6FTm4Xp5HBqOLP6MbneDOey?usp=sharing

База НН https://drive.google.com/file/d/1XH07dAr4LPn7ekj-54Y5ShOes67wBbN9/view

База https://drive.google.com/file/d/1FMzuCJI47Szhnruh-5wNtyZMmQmAOtK3/view

# 16

**Обучение с подкреплением**

Описание занятия
Цель урока.
Познакомить с подходами, лежащими в основе RL (reinforcement learning,обучение с подкреплением).

Результат урока.
Вы узнаете основные концепции, лежащие в основе обучения с подкреплением и изучите два основных алгоритма Policy Gradient и DQN. Научитеcь обучать агентов в виртуальном окружении от Open AI Gym. 

Теоретическая часть.
В видео рассматривается: 
1. Общий обзор задачи обучение с подкреплением.
2. Отличие задачи "обучение с подкреплением" от задач "обучение с учителем и "обучение без учителя".
3. Общая постановка задачи. Взаимодействие агента со средой.
4. Область применения обучения с подкреплением.
5. Популярные алгоритмы.
5.1. Policy Gradient 
5.2. DQN

Место в курсе.
Обучение с подкреплением - это одна из «вершин» курса. Очень интересная, но сложная тема. Приступать к её изучению рекомендуется если вы хорошо знакомы с тем, как создавать нейронные сети, какие основные слои (включая сверточные) используются в нейронных сетях, а также у вас есть хороший опыт подбора и обучения различных архитектур. Для самостоятельного изучения рекомендованных туториалов желательно владение ООП. 

Необходимые материалы: 

Презентация https://docs.google.com/presentation/d/1Pb4KLHTXz0xL6o10xE6o4k_jynLpwLXIqEoGIltIt3Q/edit?usp=sharing

Методичка https://drive.google.com/file/d/1vCP-jN2BukMu-0IITp-4bC2xznNYqYQr/view?usp=sharing

Ноутбук https://colab.research.google.com/drive/1dh9aigGNbLY2LoW5MBKnRZ7iYaCo5Kyn?usp=sharing
 
# 17

**Генерация текста**

# 18


# 19


# 20
