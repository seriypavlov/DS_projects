# DS проекты
    Data Science проекты Яндекс.Практикум  
    Проекты из списка ниже, находятся в соответствущей папке с таким же названием в репозитории.  
    При клике по названию проекта, попадаете в целевую папку проекта.  
    Файл DESCRIPTION.MD, в каждой папке, содержит краткое описание проекта, основных пунктах 
    и целях исследования, а так же библиотеки, используемые для выполнения проекта.
<br> 


## Список проектов
    - Проект. Выпускной проект. Телеком -  исследование оттока клиентов
    - Проект. Компьютерное зрение
    - Проект. Аналитика в авиакомпании
    - Проект. Прогнозирование тональной окраски комментариев
    - Проект. Прогнозирование количества заказов такси
    - Проект. Определения стоимости автомобиля
    - Проект. Защита персональных данных клиентов страховой компании  
    - Проект. Предсказание коэффициента восстановления золота  
    - Проект. Поиск прибыльных нефтяных месторождений
    - Проект. Отток клиентов
    - Проект. Рекомендация тарифов
    - Проект. Исследование игровых платформ
    - Проект. Определение перспективного тарифа для телеком компании
    - Проект. Исследование объявлений о продаже квартир
    - Проект. Исследование надёжности заёмщиков
<br> 

## Описания проектов
### [Проект. Прогнозирование тональной окраски комментариев](https://github.com/seriypavlov/DS_projects/tree/master/Проект.%20Прогнозирование%20тональной%20окраски%20комментариев)   
Интернет-магазин запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.
#### Результат: Для данной задачи лучшая для заказчика в плане качества предсказания, скорости предсказания, время обучения, является модель - LogisticRegression.
#### Стек: Pandas, Numpy, Seaborn, SKlearn, Re, Nltk, Torch, Transformers, XGBoost, Catboost, LightGBM
<br>


### [Проект. Прогнозирование количества заказов такси](https://github.com/seriypavlov/DS_projects/tree/master/Проект.%20Прогнозирование%20количества%20заказов%20такси)   
Компания такси собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. Построить модель для такого предсказания.
#### Результат: Наиболее оптимальной для поставленной задачи "Прогнозирования количество заказов такси на следующий час" является XGBRegressor.
#### Стек: Pandas, Numpy, Matplotlib, SKlearn, XGBoost, Catboost, LightGBM
<br>

### [Проект. Определения стоимости автомобиля](https://github.com/seriypavlov/DS_projects/tree/master/Проект.%20Определения%20стоимости%20автомобиля)   
Сервис по продаже автомобилей с пробегом разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. В вашем распоряжении исторические данные: технические характеристики, комплектации и цены автомобилей. Нужно построить модель для определения стоимости.  
#### Результат: Для данной задачи было обучено несколько моделей. Лучшая в плане качества предсказания, скорости предсказания, времени обучения оказалась - LGBMRegressor. Т.к. лучше всего справляется с поставленной задачей.
#### Стек: Pandas, Numpy, Matplotlib, Seaborn, SKlearn, XGBoost, Catboost, LightGBM
<br>

### [Проект. Защита персональных данных клиентов страховой компании](https://github.com/seriypavlov/DS_projects/tree/master/Проект.%20Защита%20персональных%20данных%20клиентов%20страховой%20компании) 
Необходимо защитить данные клиентов страховой компании. Разработать метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию. Обосновать корректность его работы. Нужно защитить данные, чтобы при преобразовании качество моделей машинного обучения не ухудшилось.   
#### Результат: Предложенный алгоритм преобразования данных справляется для решения задачи шифрования данных, полностью удовлетворяет поставленной задаче Защиты персональных данных клиентов страховой компании.
#### Стек: Pandas, Numpy, Matplotlib, Seaborn, SKlearn
<br>

### [Проект. Предсказание коэффициента восстановления золота](https://github.com/seriypavlov/DS_projects/tree/master/Проект.%20Предсказание%20коэффициента%20восстановления%20золота)
Необходимо подготовить прототип модели машинного обучения для компании, разрабатывающей решения для эффективной работы промышленных предприятий.Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды. В распоряжении данные с параметрами добычи и очистки. Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками. 
#### Результат: Обученная модель  Random Forest подходит для предсказания коэффициент восстановления золота из золотосодержащей руды, как для чернового концентрата, так и финального концентрата. Тем самым может оптимизировать производство, и заранее предсказывать, если предприятие будет с убыточными характеристиками.
#### Стек: Pandas, Numpy, Matplotlib, Seaborn, SKlearn  
<br> 

### [Проект. Поиск прибыльных нефтяных месторождений](https://github.com/seriypavlov/DS_projects/tree/master/Проект.%20Поиск%20прибыльных%20нефтяных%20месторождений)
Для добывающей компании нужно решить, где бурить новую скважину. Предоставлены пробы нефти в трёх регионах: в каждом 10 000 месторождений, где измерили качество нефти и объём её запасов. Необходимо построить модель машинного обучения, которая поможет определить регион, где добыча принесёт наибольшую прибыль. Проанализировать возможную прибыль и риски техникой Bootstrap.  
#### Результат: Обученная модель Линейная регрессия предсказывает наличие запасов нефти с точность до 0.9 тыс.баррелей, определен регион с максимальной прибылью при минимальных рисках.
#### Стек: Pandas, Numpy, Scipy, SKlearn, Bootstrap  
<br> 

### [Проект. Отток клиентов](https://github.com/seriypavlov/DS_projects/tree/master/Проект.%20Отток%20клиентов)
Из банка стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых. Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Предоставлены исторические данные о поведении клиентов и расторжении договоров с банком.  
#### Результат: Обученную для задачи классификации модель можно использовать для прогнозирования, уйдёт клиент из банка в ближайшее время или нет.
#### Стек: Pandas, Matplotlib, SKlearn  
<br> 

### [Проект. Рекомендация тарифов](https://github.com/seriypavlov/DS_projects/tree/master/Проект.%20Рекомендация%20тарифов)
Оператор мобильной связи выяснил: многие клиенты пользуются архивными тарифами. Они хотят построить систему, способную проанализировать поведение клиентов и предложить пользователям новый тариф: «Смарт» или «Ультра». В распоряжении данные о поведении клиентов, которые уже перешли на эти тарифы. Нужно построить модель для задачи классификации, которая выберет подходящий тариф. 
#### Результат: Построенна модель для задачи классификации, способная подобрать для пользователей, пользующихся архивными тарифами, более подходящий тариф («Смарт» или «Ультра»).
#### Стек: Pandas, SKlearn  
<br> 

### [Проект. Исследование игровых платформ](https://github.com/seriypavlov/DS_projects/tree/master/Проект.%20Исследование%20игровых%20платформ)
Интернет-магазине продаёт по всему миру компьютерные игры. Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы. Нужно выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.  
#### Проведен анализ: Потенциально прибыльных платформ, жанров игр; портрет пользователя для рекламных компаниях в каждом регионе.  
#### Стек: Pandas, Numpy, Scipy, Math, Matplotlib, Seaborn  
<br> 

### [Проект. Определение перспективного тарифа для телеком компании](https://github.com/seriypavlov/DS_projects/tree/master/Проект.%20Определение%20перспективного%20тарифа%20для%20телеком%20компании)
Клиентам оператора сотовой связи предлагают два тарифных плана: «Смарт» и «Ультра». Чтобы скорректировать рекламный бюджет, коммерческий департамент хочет понять, какой тариф приносит больше денег. Необходимо сделать предварительный анализ тарифов на небольшой выборке клиентов. В распоряжении данные 500 пользователей. Нужно проанализировать поведение клиентов и сделать вывод — какой тариф лучше.   
#### Проведен анализ: Оптимальный тариф для пользователей, Прибыльный тариф для оператора сотовой связи
#### Стек: Pandas, Numpy, Scipy, Math, Matplotlib, Seaborn  
<br> 

### [Проект. Исследование объявлений о продаже квартир](https://github.com/seriypavlov/DS_projects/tree/master/Проект.%20Исследование%20объявлений%20о%20продаже%20квартир)
В распоряжении данные сервиса Яндекс.Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктов за несколько лет. Нужно научиться определять рыночную стоимость объектов недвижимости. Это позволит построить автоматизированную систему: она отследит аномалии и мошенническую деятельность.  
#### Проведен анализ: Зависимости цены квартиры от удаленности от центра, количества комнат, типа этажности квартиры, даты размещения (дня недели, месяца, года)
#### Стек: Pandas, Matplotlib  
<br> 

### [Проект. Исследование надёжности заёмщиков](https://github.com/seriypavlov/DS_projects/tree/master/Проект.%20Исследование%20надёжности%20заёмщиков)  
Влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок? Входные данные от банка — статистика о платёжеспособности клиентов. Результаты исследования будут учтены при построении модели кредитного скоринга.    
#### Проведен анализ: Зависимости возврата кредита в срок от наличия детей, семейного положения, уровня дохода, цели кредита, возраста и образования.    
#### Стек: Pandas  
