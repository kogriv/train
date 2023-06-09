# train

В репозиториии размещены мои учебные проекты.

01_real_estate - исследование объявлений о продаже недвижимости. В проекте значительную часть занимает предварительная обработка данных. Здесь включена написанная мной функция:
- для построения матрицы совместного появления пропусков в различных полях
- для построения распределения значений (разбиения по корзинам) расчетных полей при заданном условии в базовом поле (например- как распределены значения в поле "площадь квартиры" в строках, отобранных по условию наличия пропусков в поле "высота потолков")

02_videogame_market - исследование рынка видеоигр. Предобработка данных, проверка статгипотез.

03_ml_intro - первый проект с использованием моделей МО- поиск ГП в обычных циклах

04_ml_imbalance - работа с несбалансированными классами, дамми-кодирование

05_wells - применение бутстрепа

06_dredge - задача разобраться в достаточно большом (в плане количества полей) и не очевидном (с точки зрения привычных действих по делению на обучающие и тестовые выборки) с первого взгляда датасете. Использование кастомной метрики

07_GBM - работа с большим количеством категориальных признаков

08_time_series - разложение ряда, поиск значимых частот (периодограмма), красивый график

08_nlp_without_nn - обработка текстов (классификация токсичности) - не использовались нейросетевые модели, применен пайплайн для гридсерча