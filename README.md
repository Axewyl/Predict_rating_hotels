# Проект-3. Исследование данных HR-агенства c помощью статистические тестов в контексте EDA.

## Оглавлелние

[1. Описание проекта](https://github.com/Axewyl/Predict_rating_hotels/blob/master/README.md#Описание-проекта)

[2. Какой кейс решаем?](https://github.com/Axewyl/Predict_rating_hotels/blob/master/README.md#Какой-кейс-решаем)

[3. Краткая информация о данных](https://github.com/Axewyl/Predict_rating_hotels/blob/master/README.md#Краткая-информация-о-данных)

[4. Этапы работы над проектом](https://github.com/Axewyl/Predict_rating_hotels/blob/master/README.md#Этапы-работы-над-проектом)

[5. Результат](https://github.com/Axewyl/Predict_rating_hotels/blob/master/README.md#Результаты)

[6. Авторы](https://github.com/Axewyl/Predict_rating_hotels/blob/master/README.md#Авторы)

[7. Выводы](https://github.com/Axewyl/Predict_rating_hotels/blob/master/README.md#Выводы)

### Описание проекта

Представьте, что вы работаете датасаентистом в компании _Booking_. Одна из проблем компании — это нечестные отели, которые накручивают себе рейтинг. Одним из способов нахождения таких отелей является построение модели, которая предсказывает рейтинг отеля. Если предсказания модели сильно отличаются от фактического результата, то, возможно, отель играет нечестно, и его стоит проверить.

Оригинальный датасет: [“Booking reviews” (kaggle.com)](https://www.kaggle.com/competitions/sf-booking/data)

### Какой кейс решаем

Построение модели максимально точно предсказывающую рейтиг отеля.

**Описание задачи:**
Задачу, которая стоит перед нами, можно свести к пяти пунктам:

1. Удаление строковых значений.
2. Очистка от пропущенных значений.
3. Создание новых признаков.
4. Преобразование признаков.
5. Отбор признаков.

**Метрика качества**

- Построенная модель оцениваются по метрике MAPE(mean_absolute_percentage_error).

_MAPE_: чем она меньше, тем лучше.

**Что практикуем**

- Учимся проводить предобработку данных;
- исследовать первичную информацию;
- проводить разведовательный анализ данных;
- преобразовывать признаки, добавлять новые;
- выдвигать гипотизы и проводить тестирование;
- делать обоснованные выводы на основе тестов и кореляции, графиков с целью улучшения показателей MAPE.

### Краткая информация о данных

Исходная информация, подробнее [здесь](https://www.kaggle.com/competitions/sf-booking).

### Этапы работы над проектом

1. Постановка проблемы;
2. Описание данных первичная оценка;
3. Очистка данных;
4. Разведовательный анализ данных;
5. Нормализация признаков;
6. Моделирование;
7. Выводы.

### Результаты

Результатом служит значения показателя MAPE. На его основе строится предсказания для _submission_.

### Авторы

- [Andrey](https://t.me/Axewyl)

### Выводы

**Основное исследование:**

Благодаря данному проект мы смогли:

- построить обучающую модель;
- предсказать реультат для тестовых данных и спрогназировать _reviewer_score_ (оценка, которую рецензент поставил отелю на основе своего опыта);
- разобрать и добавить новые признаки;
- дать оценку по метрике качества MAPE;
- с помощью тестов статестической значимости и таблицы корреляции выделить и оставить, наиболее важные признаки;

**Дополнительтное исследование:**

- в силу ораниченного времени и в качестве дальнешей работы рекомендовал бы разобрать новые признаки и поработать над уже полученными.

:arrow_up:[к оглавлнию](https://github.com/Axewyl/HR-Agency-Research/blob/master/README.md#Оглавлелние)
