# DS_practicum
*Учебные проекты Яндекс Практикум*
 
**[1. Определение стоимости автомобилей](https://github.com/mrOstrovsky/DS_practicum-/blob/main/p_autoprice.ipynb)**

Сервис по продаже автомобилей с пробегом разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля.

В распоряжении исторические данные: технические характеристики, комплектации и цены автомобилей.

**Задача:** Построить модель для определения стоимости автомобиля.

**Инструменты:** ``pandas_profiling``, ``matplotlib``, ``pandas``, ``seaborn``, ``numpy``, ``catboost``, ``sklearn``, ``make_column_transformer``, ``train_test_split``, ``StandardScaler``, ``OrdinalEncoder``, ``GridSearchCV``, ``OneHotEncoder``, ``mean_squared_error``, ``LinearRegression``, ``DecisionTreeRegressor``, ``RandomForestRegressor``, ``Ridge``, ``LGBMRegressor``


**[2. Прогноз оттока клиентов](https://github.com/mrOstrovsky/DS_practicum-/blob/main/p_betabank.ipynb)**

Из банка стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.

Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Предоставлены исторические данные о поведении клиентов и расторжении договоров с банком.

**Задача:** Спрогнозировать отток клиентов.

**Инструменты:** ``pandas_profiling``, ``matplotlib``, ``pandas``, ``train_test_split``, ``shuffle``, ``StandardScaler``, ``OrdinalEncoder``, ``RobustScaler``, ,``DecisionTreeClassifier``, ``RandomForestClassifier``, ``LogisticRegression``, ``f1_score``, ``roc_curve``, ``roc_auc_score``


**[3. Прогноз продаж в интернет-магазине](https://github.com/mrOstrovsky/DS_practicum-/blob/main/p_games.ipynb)**

В распоряжении данные интернет-магазина, который продаёт по всему миру компьютерные игры. Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы до 2016 года. Выявим закономерности, определяющие успешность игры, чтобы спланировать рекламные кампании. ESRB (Entertainment Software Rating Board) — это ассоциация, определяющая возрастной рейтинг компьютерных игр. ESRB оценивает игровой контент и присваивает ему подходящую возрастную категорию, например, «Для взрослых», «Для детей младшего возраста» или «Для подростков».

**Задача:** Исследование продаж компьютерных игр в различных регионах и определение стратегии рекламной компании.

**Инструменты:** ``pandas``, ``numpy``, ``scipy``, ``math``, ``matplotlib``, ``seaborn``


**[4. Прогнозирование заказов такси](https://github.com/mrOstrovsky/DS_practicum-/blob/main/p_prognoz_taxi.ipynb)**

Компания собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час.

**Задача:** Модель предсказания заказов такси на следующий час.

**Инструменты:** ``pandas``, ``numpy``,  ``matplotlib``, ``seaborn``, ``statsmodels``, ``sklearn``, ``adfuller``, ``seasonal_decompose``, ``mean_squared_error``, ``train_test_split``, ``TimeSeriesSplit``, ``GridSearchCV``, ``LinearRegression``, ``Ridge``, ``DecisionTreeRegressor``, ``RandomForestRegressor``, ``LGBMRegressor``


**[5. Выбор локации для скважины](https://github.com/mrOstrovsky/DS_practicum-/blob/main/p_skvazina.ipynb)**

Предоставлены пробы нефти в трёх регионах: в каждом 10 000 месторождений, где измерили качество нефти и объём её запасов. Постройте модель машинного обучения, которая поможет определить регион, где добыча принесёт наибольшую прибыль.

**Задача:** Модель предсказаний прибыли компании и выбор прибыльных регионов для разработки нефти.

**Инструменты:** ``pandas_profiling``, ``pandas``, ``numpy``,  ``matplotlib``, ``seaborn``, ``scipy``, ``RandomState``, ``sklearn``, ``train_test_split``, ``LinearRegression``, ``mean_squared_error``, ``RobustScaler``, ``bootstrap``


**[6. Прогнозирование температуры плавления стали](https://github.com/mrOstrovsky/DS_practicum-/blob/main/p_tempsteel.ipynb)**

Чтобы оптимизировать производственные расходы, металлургический комбинат решил уменьшить потребление электроэнергии на этапе обработки стали. 

**Задача:** Построить модель, которая предскажет температуру.

**Инструменты:** ``shap``, ``pyod``, ``pandas``,  ``matplotlib``, ``seaborn``, ``numpy``, ``sklearn``, ``sklearn``, ``train_test_split``, ``StandardScaler``, ``mean_absolute_error``, ``cross_val_score``, ``GridSearchCV``, ``math``, ``LinearRegression``, ``LGBMRegressor``, ``RandomForestRegressor``


**[7. Классификация токсичных комментариев](https://github.com/mrOstrovsky/DS_practicum-/blob/main/p_text.ipynb)**

Интернет-магазин запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.

**Задача:** Построить модель классификации токсичных комментариев. 

**Инструменты:** ``pandas``, ``numpy``, ``matplotlib``,  ``seaborn``, ``re``, ``pymystem3``, ``tqdm``, ``wordnet``, ``stopwords``, ``WordNetLemmatizer``, ``Pipeline``,  ``TfidfVectorizer``, ``TfidfTransformer``, ``f1_score``, ``GridSearchCV``, ``LogisticRegression``, ``SGDClassifier``, ``LinearSVC``, ``RandomForestClassifier``, ``DecisionTreeClassifier``, ``LGBMClassifier``, ``shuffle``, ``nltk``, ``sklearn``


**[8. Защита персональных данных клиентов](https://github.com/mrOstrovsky/DS_practicum-/blob/main/p_zashitadannyh.ipynb)**

Нужно защитить данные клиентов страховой компании. Разработайте такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию. Обоснуйте корректность его работы.

**Задача:** Нужно защитить данные, чтобы при преобразовании качество моделей машинного обучения не ухудшилось.

**Инструменты:** ``pandas_profiling``, ``pandas``,  ``numpy``, ``sklearn``, ``train_test_split``, ``LinearRegression``, ``r2_score``, ``mean_squared_error``


**[9. Восстановление золота из руды](https://github.com/mrOstrovsky/DS_practicum-/blob/main/p_zoloto.ipynb)**

Компания разрабатывает решения для эффективной работы промышленных предприятий.

Предоставлены данные с параметрами добычи и очистки.

**Задача:** Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды.

**Инструменты:** ``pandas``, ``matplotlib``,  ``seaborn``, ``sklearn``, ``LinearRegression``, ``cross_val_score``, ``cross_val_predict``, ``LinearRegression``, ``DecisionTreeRegressor``, ``RandomForestRegressor``,  ``DummyRegressor``, ``GridSearchCV``, ``make_scorer``, ``mean_absolute_error``, ``StandardScaler``, ``namedtuple``, ``numpy``


**[10. Компьютерное зрение. Определение возраста покупателей](https://github.com/mrOstrovsky/DS_practicum-/blob/main/p_zrenie.ipynb)**

Сетевой супермаркет внедряет систему компьютерного зрения для обработки фотографий покупателей. 

**Задача:** Построить модель, которая по фотографии определит приблизительный возраст человека.

**Инструменты:** ``pandas``, ``tensorflow``,  ``keras``, ``fashion_mnist``, ``Dense``, ``Sequential``, ``Adam``, ``Dropout``, ``Flatten``, ``Conv2D``,  ``MaxPooling2D``, ``AvgPool2D``, ``ImageDataGenerator``, ``ResNet50``, ``matplotlib``, ``seaborn``, ``numpy``, ``PIL``

