**Ход работы:**

**01 - Предобработка.ipynb**
*    беглый анализ датасета, первичная предобработка датасета, сохранение итогов в XLS и CSV

**02 - Аналитика.ipynb**
*    создание основного класса для работы с датасетом, перенос туда загрузки и первичной подготовки датасета
*    создание корреляционных матриц для дальнейшего анализа
*    более подробная аналитика датасета
*    эксперименты по анализу качества кредита клиентов
*    более глубокий анализ данных, создание системы рейтинга клиентов на основе данных для выявления выбросов в датасете (либо для корректировки выставленного заказчиком рейтинга в дальнейшем)

**03 - Подготовка, Autokeras.ipynb**
*    все предыдущие эксперименты по анализу и обработке данных собраны, дополнены и перенесены в основной класс python
*    сделана дозагрузка и загрузка сразу нескольких датасетов для последующей пакетной обработки
*    сделана подготовка датасетов для Autokeras
*    проведены первые эксперименты в Autokeras

**04 - AutoML.ipynb**
*    доработан класс для обработки полного датасета
*    проведены эксперименты с обучением с LabelEncoder и нормированием данных

**05 - Обработка.ipynb**
*    проведены эксперименты по обработке данных, выявление ошибок и выбросов датасета
*    переделан класс обработки датасета под выявленные ошибки и выбросы датасета
