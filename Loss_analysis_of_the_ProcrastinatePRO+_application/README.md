# Описание проекта Анализ убытков приложения ProcrastinatePRO+.

Развлекательное приложение Procrastinate Pro+. Несмотря на огромные вложения в рекламу, последние несколько месяцев компания терпит убытки. Необходимо разобраться в причинах этой ситуации.

# Цель:
Определить  по какой причине компания терпит убытки

# Задачи:
-   Определить откуда приходят пользователи и какими устройствами они пользуются;
-  Рассчитать  сколько стоит привлечение пользователей из различных рекламных каналов;
-   Рассчитать сколько денег приносит каждый клиент;
-   Определить когда расходы на привлечение клиента окупаются;
-   Выявить какие факторы мешают привлечению клиентов.
  
# Этапы исследования:
-  Обзор данных.
- Предобработка данных.
- Анализ данных.
- Маркетинг.
- Оценка окупаемости рекламы.
- Выводы и рекомендации.

# Стек проекта:
 Обработка данных, статистический тест, LTV, CAC, когортный анализ
  
**Реализованные  библиотеки:**

-   `pandas`
-   `numpy`
-   `seaborn`
-   `matplotlib`

# Вывод

Причины, неэффективности привлечения пользователей:

- Можно заметить, что стоимость рекламы значительно выросла для пользователей iPhone и Mac и окупаемость по этим устройствам хуже всего. Окупается реклама только для пользователей PC.
-   Скорее всего, причина в технической проблеме. Возможно есть проблема с оптимизацией приложения Procrastinate Pro+ для ios устройств (это ведущая платформа для США)  
-   Не стоит вкладывать большое количество средств в рекламную систему TipTop, она неэффективна. Предполагаем, что данная сеть, популярна в других странах
    
Рекомендации для отдела маркетинга.

-   Стоит обратить внимание на каналы откуда привлекаются платящие пользователи PC, потому что они удерживаются лучше всего
-   Самый высокий LTV у канала lambdaMediaAds. Нужно увеличить ROI, с помощью более дешевого канала привлечения для этих пользователей
- Платящим пользователям нравится продукт, можно попробовать найти подешевле канал привлечения для этих пользователей. 
- Нужно искать новые каналы для привлечения пользователей из стран: UK и Germany. 
- Стоит обратить внимание на 3 недооценённых канала с наивысшим ROI: Yrabbit, MediaTornado, lambdaMediaAds
