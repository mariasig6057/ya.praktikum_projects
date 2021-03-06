**Задача проекта**

Cегментация покупателей по профилю потребления на основе транзакций заказов в интернет-магазине товаров для дома.

**Что было сделано**

1. Категоризация товаров (на основе данных из веба и путем выделения наиболее популярных товаров)
2. EDA 
	* выявление и обработка аномалий 
	* исследование характеристик заказов
	* разделений оптовых и розничных заказов
3. Расчет и изучение бизнес-метрик по розничным заказам.
4. Сегментирование розничных покупателей на основе сезонности и выявление основных характеристик для каждого сегмента. 
Проверка гипотезы о значимости различий среднего чека выделенных сегментов (с помощью `T-теста`).
5. Сегментирование розничных покупателей на основе всех характеристик с помощью алгоритма кластеризации (`k-means`). 
Проверка гипотезы о значимости различий среднего чека выделенных кластеров (с помощью `T-теста`).
6. Построение дашборда в `Tableau Public` с количеством уникальных заказов и покупателей.

**Используемые Python-библиотеки**

`pandas`, `numpy`, `matplotlib`, `seaborn`, `requests`, `bs4`, `re`, `scipy`, `collections`, `itertools`, `sklearn`
