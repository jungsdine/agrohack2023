# agrohack2023
Алгоритм анализа резюме для кластеризации схожих профессий и представление их в графе.

HOW TO START 

DS-решение кластеризации можно найти и протестировать на Google.Colab
[](https://colab.research.google.com/drive/1oojLGBzpBCaCp6e9wDd_sbv7Y-qboV-k?usp=sharing#scrollTo=DqO6IlAeX3L)

Визуализация графа лежит на гитхабе по ссылке ниже, доступная для скачивания и тестирования
[](https://github.com/BIZHAN28/Agrocode-2023)

| Алгоритм | Примерное время работы |
|----------|----------|
| Парсинг    | ~120  с |
| Токенизация    | ~30  с |
| Кластеризация    | 20 c   |
| Построение графа  | ~16  с |


Дальнейшее развитие:
+ Большая автоматизация парсинга за счет использования бОльшей текстовой модели (доучить ByT5, или воспользоваться chatGPT/LLama)
+ Автоматизировать выбор размера кластеров
+ Добавить возможность смотреть отдельные кластеры на фронтэнде
+ Добавить больше контекста для векторизации (образование, опыт работы, описание профессий)

P.S.
Как выглядят кластеры при k=40 (количество кластеров)

![image](https://github.com/jungsdine/agrohack2023/assets/125709080/cb182ea4-e054-4b1a-824e-780ad9365f89)
