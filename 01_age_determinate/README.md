# Определение возраста покупателей
## Описание проекта

Требуется постройть модель, которая по фотографии определит приблизительный возраст человека. В нашем распоряжении набор фотографий людей с указанием возраста.

## Навыки и инструменты

- **python**
- **pandas**
- **matplotlib**
- **seaborn**
- tensorflow.keras.preprocessing.image.**ImageDataGenerator**
- tensorflow.keras.applications.resnet50.**ResNet50**
- tensorflow.keras.layers.**GlobalAveragePooling2D**
- tensorflow.keras.layers.**Dense** 
- tensorflow.keras.models.**Sequential**
- tensorflow.keras.optimizers.**Adamax**

## Краткий вывод
Созданная модель показала достаточное качество со значением MAE = 5.90, что ниже целевого показателя равного 8. Таким образом, задача создания модели определения приблизительного возраста человека по фотографии решена.

