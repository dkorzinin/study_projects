#### Ответ рецензента:
*Татьяна Никитина:*
Дмитрий, привет.
Меня зовут Татьяна Никитина. Я проверяю твой проект.
Ты проделал большую работу над проектом и справился с ней успешно.
Мне понравилось:

- логичность, структурированность, цельность проекта;
- наличие и уместность визуализаций;
- подробное описание хода исследования и промежуточные выводы.

Это получилось хорошо.
Давай посмотрим зоны роста – те области, в которых ты можешь сделать свой проект лучше:

- провести изучение данных и EDA  (дубликаты, пропуски, оценка выбросов и т.д.)
- отключить предупреждение [FutureWarning](https://www.grepper.com/answers/21493/python+suppress+warnings+in+function) в финальном варианте работы;
- использовать настройки вывода [таблиц](https://towardsdatascience.com/8-commonly-used-pandas-display-options-you-should-know-a832365efa95) : ограничить число значащих цифр после запятой, отобразить проценты;
- цельности работе придаст небольшое вступление с описанием  области и задач исследования, исходных датасетов.

Давай посмотрим конкретику по задачам.
1.  7/7
Логика решения и ответ задачи корректны.
Хороший лаконичный код.
2.  5/5
Все верно.
Здорово, что комментируешь ход решения. Можно обобщать и выносить текстовые блоки в ячейки Markdown.
3.  5/5
Решение корректное.
Ты рассмотрел ситуацию с разных сторон и предложил два подхода к определению средних сроков сдачи. Это прекрасно.
4. 7/8
Задача выполнена правильно.
Небольшая шероховатость - способ подсчета популярности курса. Здесь лучше использоватьid_student и функцию nunique(). У некоторых студентов есть регистрации на курс в разных семестрах, соответственно у тебя возникает двойной подсчет. Аналогично обстоит дело и с ситуацией отмены регистрации.
Было бы здорово прокомментировать полученный результат.
5. 10/10
Ты прекрасно разобрался с написанием функции.
Очень здорово, что ты сопровождаешь процесс подробными комментариями. Это полезно, особенно, когда ты решишь использовать функции, которые написал ранее.  Для документирования функций используются многострочные комментарии. Правила документирования описаны в PEP 257.
6. 35/35
Сегментация студентов проведена корректно.

Здорово, что ты проанализировал каждый параметр  и выбрал наиболее подходящий способ выделения кластеров.
Визуализации заслуживают отдельного спасибо. Здесь только стоит сделать подписи заголовков.
Отлично, что ты исследовал результат кластеризации. Можно дополнить небольшими рекомендациями по работе с сегментами.

Итоговый результат 69 баллов - проект принят.

#### Ответ рецензенту:
*Дмитрий Корзинин:*
Татьяна, добрый день! Большое спасибо за рецензию и за высокую оценку проекта.
Я переделал задание №4 с учетом возможных двойных подсчетов студентов которые регистрировались на один и тот же курс в разных семестрах. 
Действительно - есть двойные регистрации, однако это не повлияло на порядок курсов в рейтинге регистраций и рейтинге отмены регистрации. 
Отдельный ноутбук с заданием №4 прикрепил [int_proj_4](int_proj_4.ipynb)

#### Ответ рецензента:
*Татьяна Никитина:*
Дмитрий,
4. 8/8
ты верно отмечаешь, что рейтинг останется прежним. Альтернативный подход к определению рейтинга имеет право на жизнь  в случае его обоснования.  
Итоговый результат 70 баллов - проект принят.
