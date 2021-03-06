# DS_projects

В этом репозитории выложены мои проекты, выполненные в рамках прохождения обучения на курсах Яндекс.Практикум по специальности Специалист по Data Science.

**[Папка 01 - Проект "Исследование надежности заемщиков"](https://github.com/Kirill-Kiselev/DS_project/tree/main/01_Research_of_borrowers_reliability)**
<br>На основе данных о клиентах банка проведено исследование надежности заемщиков. Определены категории клиентов, составлены портреты надежных и ненадежных замещиков.

**[Папка 02 - Проект "Исследование объявлений о продаже квартир"](https://github.com/Kirill-Kiselev/DS_project/tree/main/02_Apartments_sale_announcements_research)**
<br>В рамках проекта исследован датасет, содержащий архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктов. Провдена предобработка данных, определено какие факторы больше всего влияют на стоимость квартиры. Определены зависимости стоимости квартир от различных факторов.

**[Папка 03 - Проект "Определение перспективного тарифа для телеком-компании"](https://github.com/Kirill-Kiselev/DS_project/tree/main/03_Determination_of_a_promising_tariff_for_a_telecom_company)**
<br>Исследованы данные из пяти датасетов с информацией о клиентах телеком-компании. Провдена предобработка данных. Добавлены необходимые метрики. Построены гистограммы по всем показателям. После проведения всех необходимых преобразований и рассчетов проверены статистические гипотезы. Даны выводы по определению перспективного тарифа.

**[Папка 04 - Проект "Анализ рынка компьютерных игр"](https://github.com/Kirill-Kiselev/DS_project/tree/main/04_Analysis_of_the%20_video_games_market)**
<br>Для проведения исследовательсвокго и статистического анализа предоставлена генеральная совокупностьданных по рынку компьютерных игр выходивших с 1980 по 2016 годы на различных платформах. Цель выполнения проекта - выявить определяющие успешность игры закономерности. Провдена предобработка данных. Добавлены необходимые метрики. Построены гистограммы и графики по различным показателям. Проверены статистические гипотезы. Даны выводы по закономерностям определяющим успешность игр.

**[Папка 05 - Проект "Рекомендация тарифов телеком-компании"](https://github.com/Kirill-Kiselev/DS_project/tree/main/05_Tariff_recommendation)**
<br>Для построения модели рекомендации тарифов предоставлен датасет, содержащий информациию о клиентах телеком-компании. После загрузки данных, проанализированы средние показатели по звонкам, расходу минут, SMS и мегабайтов у пользователей. Датасет разделен на выборки - обучающую, валидационную и тестовую. Подобраны оптимальные гиперпараметры моделей. Модели проверены на тестовой выборке. Получена максимальная метрика accuracy. Проведена проверка модели на адекватность.

**[Папка 06 - Проект "Прогнозирование оттока клиентов банка"](https://github.com/Kirill-Kiselev/DS_project/tree/main/06_Customer_churn_prediction)**
<br>Для построения модели прогнозирующей отток клиентов банка дан датасет, содержащий данные о клиентах. В ходе проекта проведено исследование баланса классов, удалены ненужные для обучения модели столбцы. Категориальные признаки преобразованы в численные техникой прямого кодирования - *OHE*. Выполнено масштабирование признаков методом стандартизации. Рассчитаны значения метрик *F1* и *AUC-ROC*, построены ROC-кривые. По результатам уменьшения дисбаланса классов методом *Upsamplig* и обучения моделей при сбалансированных условиях, определена лучшая модель. Лучшая модель проверена на тестовых данных, определены метрики качества *F1-мера*, *AUC-ROC*. Сделаны выводы.

**[Папка 07 - Проект "Определение наиболее прибыльного региона для добычи нефти"](https://github.com/Kirill-Kiselev/DS_project/tree/main/07_Determining_the_most_profitable_region_for_oil_production)**
<br>Для построения модели для определения региона, где добыча принесёт наибольшую прибыль предоставлены 3 датасета с данными о качестве нефти в трех регионах. Обучены 3 модели Линейной регрессии для предсказания вероятных запасов нефти по скважинам в регионе. Определены метрики *RMSE* для каждого региона. Техникой бутстреп определены средняя прибыль, 95%-й доверительный интервал и риск убытков в каждом из трех регионов. Выбран наиболее прибыльный регион для добычи.

**[Папка 08 - Проект "Предсказание коэффициента восстановления золота из золотосодержащей руды"](https://github.com/Kirill-Kiselev/DS_project/tree/main/08_Gold_recovery_rate_prediction)**
<br>Для анализа данных и построения модели предоставлены 3 датасета, отражающие показатели качества очистки сырья в виде золотоносной руды. Проведена предобработка и анализ данных. Обучение моделей и проверка их на кросс-валидации позволила определить лучшие для этого модели. Подбор оптимальных параметров осуществлялся с помощью функции *GridSearchCV*. Финальным шагом стало вычисление итоговой метрики *sMAPE* для обоих моделей.

**[Папка 09 - Проект "Защита данных клиентов страховой компании"](https://github.com/Kirill-Kiselev/DS_project/tree/main/09_Protection_of_insurance_company_customer_data)**
<br>Для анализа данных и построения модели предоставлен датасет, содержащий информацию о клиентах страховой компании. Для защиты данных клиентов исходный датасет был преобразован путем умножения признаков на квадратную обратимую матрицу. Далее проведены стандартные шаги по разделению датасетов на обучающие и тестовые выборкт, обучение моделей и сравнение метрик *R2* для обеих.

**[Папка 10 - Проект "Определение рыночной стоимости автомобиля с пробегом"](https://github.com/Kirill-Kiselev/DS_project/tree/main/10_Determining_the_used_car_price)**
<br>Для анализа данных и построения модели предоставлен датасет, содержащий информацию о технических характеристиках, комплектациях и ценах автомобилей, которые размещались на площадке сервиса для продажи. Проведена предобработка и анализ данных. Обучены четыре модели. Определены оптимальные гиперпараметры и показатели метрики *RMSE* на кросс-валидации. Определены временные рамки работы всех моделей. Построены графики важности признаков. Выполнено тестирование моделей на тестовой выборке. Проведена проверка на адекватность. Даны выводы.

**[Папка 11 - Проект "Прогноз количества заказов такси (времянные ряды)"](https://github.com/Kirill-Kiselev/DS_project/tree/main/11_Number_of_taxi_orders_prediction)**
<br>Для анализа данных и построения модели предоставлен датасет, содержащий исторические данные о заказах такси в аэропортах сервиса компании такси. Проведена предобработка и анализ данных. Подобраны оптимальные гиперпараметры для четырех моделей ориентируясь на метрику *RMSE*. Проведено тестирование всех моделей, каждой из них удалось достичь требуемого показателя метрики *RMSE*. Выполнен анализ сравнительных графиков в двух масштабах. Дополнительно построены графики важности параметров. Даны выводы.

**[Папка 12 - Проект "Определение токсичных комментариев"](https://github.com/Kirill-Kiselev/DS_project/tree/main/12_Determining_of_toxic_comments)**
<br>Для анализа данных и построения модели предоставлен датасет с размеченными данными, содержащий комментарии пользователей к товарам, доступным для приобретения в интернет-магазине. Объявлен корпус текстов. Данные очищены и лемматизированы. Для векторизации текстов был использован *TfidfVectorizer()*. Полученный датасет разделен на обучающую и тестовые выборки. Подобраны оптимальные гиперпараметры для моделей. Все выбранные модели прошли проверку на адекватность в сравнении с константной моделью. Для определения качества предсказания использована метрика *F1*.
