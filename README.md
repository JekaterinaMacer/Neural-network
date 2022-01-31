# Neural-network

2

Оценка качества обучения нейросети. Почему недостаточно только функции ошибки для оценки нейросети. Что такое bias, для чего используется.

Часть 1. Теоретическая часть
В видео рассматриваются: Описание bias. Что это такое, зачем он нужен. Описание модели что такое весовые параметры и откуда они берутся. Разделение данных на обучающую, проверочную и тестовую выборки и зачем они нужны на примере базы данных MNIST (60 000 вариантов написания рукописных цифр). Схема обучения нейронной сети. Что такое переобучение, как с ним бороться. Что такое Dropout и Normalization, для чего они нужны и как улучшают качество модели. 


Глоссарий

Типы выборок:

Обучающая выборка - основной набор данных, на котором происходит обучение нейронной сети
Проверочная выборка - набор данных, на котором отслеживается качество работы сети в процессе обучения
Тестовая выборка - контрольный набор данных, на котором проверяется качество работы обученной сети

Способы формирования проверочной выборки:

validation_split - указываем процент от обучающей выборки, который будет использоваться в качестве проверочной
validation_data - указываем готовые наборы данных, которые будут использоваться в качестве проверочной выборки
Переобучение сети - ситуация, при которой сеть "заучила" исходную обучающую выборку и не способна производить обобщение данных (верно распознавать данные из проверочных и тестовых наборов)

Способы преодоления переобучения:

Dropout - принудительное "отключение" случайного числа нейронов
BatchNormalization - нормализация данных на выходе слоя
StandardScaler - класс нормализации данных (приводит переданный набор числовых данных к нормальному распределению)
