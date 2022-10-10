
# Компьютерное зрение. Определение возраста по фото

## Описание проекта

Сетевой супермаркет хочет внедрить систему компьютерного зрения для определения возраста покупателей. С ее помощью можно настроить рекомендательную систему для отдельных возрастных групп и предотвращать продажу алкоголя (и других взрослых вещей) несовершеннолетним.

## Навыки и инструменты:

 - **pandas**
 - **numpy** 
 - **matplotlib**
 - **plotly**

keras

 - tensorflow.keras.**preprocessing.image.ImageDataGenerator**
 - tensorflow.keras.**datasets.fashion_mnist**
 - tensorflow.keras.**applications.resnet.ResNet50**
 - tensorflow.keras.**layers.Conv2D, Flatten, Dense, MaxPooling2D, AvgPool2D, GlobalAveragePooling2D**
 - tensorflow.keras.**models.Sequential**
 - tensorflow.keras.**optimizers.Adam**



## Общий вывод

Построенная модель может ошибаться на, примерно, 6 лет, значит - полность отдавать ей контроль за продажей товаров несовершеннолетним нельзя. А вот для создания рекомендательной системы по возрастным группам она подойдет.

### Параметры модели:
 - **optimizer = Adam(lr=0.0001)**
 - **функия потерь - MSE**
 - **Архитектура ResNet50 с weights='imagenet'**
 - **один полносвязный слой 1024 нейрона с активацией relu**
 - **второй полносвязный слой с 5 нейронами с активацией relu**
 - **50 эпох**