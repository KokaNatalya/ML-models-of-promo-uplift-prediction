# Проект по разработке регрессионных моделей прогнозирования промо аплифта

Инициативный проект во время моей стажировки в Demand Planning Mars. Создан ряд регрессионных моделей для прогноза промо продаж, чтобы заменить ручное прогнозирование и выбирать оптимальный размер скидки, продолжительность промо для минимизации затрат на продажу, т.е. давать только те промо, которые с точки зрения эластичности будут окупаться.

Проект представляет из себя "калькулятор" в который можно ввести данные о предполагаемой товарной категории, скидке, периоде в котором будет проводиться промо и группу в которую входит клиент, которому будет предоставлена скидка (таблица с мэппингом в файле, для каждой категории товаров она своя, т.к. формируется на основе исторических объемов закупок) и получить прогноз на основе модели с наибольшим R2

### Данные
выргрузки по истории промо.
(Товарная категория, дата промо, размер скидки, клиент, фактически отгруженный объем.
 
### Библиотеки
- pandas,
- datetime
- seaborn
- matplotlib.pyplot
- numpy
- scipy
- sklearn (svm, model_selection, linear_model, metrics, neighbors, ensemble, tree)
