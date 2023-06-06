# FruitFreshness
Проект по детекции свежих фруктов на фото

#Принцип работы
Использованная база данных: https://www.kaggle.com/sriramr/fruits-fresh-and-rotten-for-classification

С помощью ssd_mobilenet_v2 (https://tfhub.dev/tensorflow/ssd_mobilenet_v2/2) из исходного изображения вырезаються фрукты и подаються на вход обученной сети.

После на фото выявляются прямоугольники в соответствии с предсказанием сети о испоченоти или свежести фрукта.
# Пример работы
![image](https://user-images.githubusercontent.com/26749528/159566571-24a1cf8a-5088-4bda-805a-54ffeffcb45d.png)
![image](https://user-images.githubusercontent.com/26749528/160108752-debf62bb-9b70-4bbf-aeae-8748e0a5bd9a.png)
![image](https://user-images.githubusercontent.com/26749528/160108812-2f0f60c7-48ab-4a82-bcc4-b5479ee77685.png)
