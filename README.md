# Классификация клиентов банка.

## Оглавление 
[1. Описание проекта](https://github.com/AleksDEF/Bank_clients_classification/blob/main/README.md#Описание-проекта)

[2. Какой кейс решаем?](https://github.com/AleksDEF/Bank_clients_classification/blob/main/README.md#Какой-кейс-решаем)

[3. Краткая информация о данных](https://github.com/AleksDEF/Bank_clients_classification/blob/main/README.md#Краткая-информация-о-данных)

[4. Этапы работы над проектом](https://github.com/AleksDEF/Bank_clients_classification/blob/main/README.md#Этапы-работы-над-проектом)

[5. Результат](https://github.com/AleksDEF/Bank_clients_classification/blob/main/README.md#Результат)

[6. Выводы](https://github.com/AleksDEF/Bank_clients_classification/blob/main/README.md#Выводы)



### Описание проекта 
Проанализировать данные последней маркетинговой кампании, выявить закономерность и найти решающие факторы, повлиявшие на то, что клиент вложил деньги именно в этот банк.

:arrow_up: [к оглавлению](https://github.com/AleksDEF/Bank_clients_classification/blob/main/README.md#Оглавление)


### Какой кейс решаем?
Построить модель машинного обучения, которая на основе предложенных характеристик клиента будет предсказывать, воспользуется он предложением об открытии депозита или нет.

### Информация о данных 
Данные о клиентах банка:
age (возраст);
job (сфера занятости);
marital (семейное положение);
education (уровень образования);
default (имеется ли просроченный кредит);
housing (имеется ли кредит на жильё);
loan (имеется ли кредит на личные нужды);
balance (баланс).
Данные, связанные с последним контактом в контексте текущей маркетинговой кампании:

contact (тип контакта с клиентом);
month (месяц, в котором был последний контакт);
day (день, в который был последний контакт);
duration (продолжительность контакта в секундах).
Прочие признаки:

campaign (количество контактов с этим клиентом в течение текущей кампании);
pdays (количество пропущенных дней с момента последней маркетинговой кампании до контакта в текущей кампании);
previous (количество контактов до текущей кампании)
poutcome (результат прошлой маркетинговой кампании).

Дата-сет используемый в анализе (RAR) - (https://github.com/AleksDEF/Gift-_shop_client_clusterization/blob/main/data_pr6.rar)

:arrow_up: [к оглавлению](https://github.com/AleksDEF/Bank_clients_classification/blob/main/README.md#Оглавление)

### Этапы работы над проектом
1. #### Произвести предобработку исходного набора данных о транзакциях.
2. #### Провести разведывательный анализ данных и выявить основные закономерности.
3. #### Сформировать набор данных о характеристиках каждого из уникальных клиентов.
4. #### Построить несколько моделей машинного обучения, решающих задачу кластеризации клиентов, определить количество кластеров и проинтерпретировать их.
:arrow_up: [к оглавлению](https://github.com/AleksDEF/Bank_clients_classification/blob/main/README.md#Оглавление)

### Результат
[Ноутбук с решением](https://github.com/AleksDEF/Bank_clients_classification/blob/main/Gift_shop_client_clusterization.ipynb)

:arrow_up: [к оглавлению](https://github.com/AleksDEF/Bank_clients_classification/blob/main/README.md#Оглавление)

### Выводы
В результате исследования было выявленно 3 сегмента клиентов:
* "Лояльные",  которые приносят наибольший доход, совершают покупки чаще всего, а давность их последней покупки небольшая.
* "Промежуточные" , которые являются активными, но покупают не так часто и много, как лояльные клиенты. 
* "Ушедшие", которые купили меньше всего товара, и их последняя покупка была совершена очень давно.

:arrow_up: [к оглавлению](https://github.com/AleksDEF/Bank_clients_classification/blob/main/README.md#Оглавление)
