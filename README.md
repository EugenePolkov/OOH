**Общее описание задачи**

Рекламное агентство арендует носители наружной рекламы (рекламные конструкции) для проведения рекламной кампании по своим клиентам.
Каждая конструкция имеет общую прайсовую цену, к которой применяется либо дисконт, либо надбавка, в зависимости от различных факторов:
- время размещения (высокий, низкий спрос)
- ценовая политика селлера
- общий бюджет клиента на рекламную кампанию по категории "Наружная реклама"

Помимо этого есть ряд характеристик, которые влияют непосредственно на прайсовую цену, но неясно насколько сильно они влияют на размер дисконта/надбавки от нее: расположение, тип конструкции, рейтинг конструкции и т.д.

**Задача**  
Предсказать сумму дисконта/надбавки от прайсовой цены, которую можно получить от селлера-оператора наружной рекламы для конкретной конструкции

**Формат входных данных**

DataSet состоит из частичной выгрузки из базы данных по сделкам за двухлетний период, которые содержит основные параметры сделки, влияющие на цену с итоговым значением дисконта /надбавки (target), а также несколько сконструированных признаков 

**Метрика качества**  
пользовательская - 95% предсказаний должны укладываться в интервал $\pm$ 5% от истинного значения




