# Прогнозирование оттока клиентов в сети отелей

Раздел | Цель | Вывод | Ключевые слова проекта | Используемые библиотеки
------------- |----------------  | --------------- | ---------------- | -----------------------
Сборный проект | Разработать систему, которая предсказывает отказ от брони. Если модель покажет, что бронь будет отменена, то клиенту предлагается внести депозит - деньги будут списаны со счёта клиента, если он всё же отменит бронь. Выявить лучшую модель для решения задачи. | Наилучший результат показывает модель решающего дерева, тк она имеет наибольшее значение точности для выбранного порога, а точность показывает долю истинно положительных ответов, то есть те бронирования, которые действительно будут отменены. Прибыль после внедрения депозитов увеличилась более чем в 2 раза, что полностью покрывает расходы на разработку модели. | Классификация, бизнес-модель  | `Pandas`, `Python`, `NumPy` `Matplotlib` `Seaborn` `Sklearn`
