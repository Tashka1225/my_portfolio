# Портфолио: аналитик данных

## Обо мне 

Привет! Меня зовут <strong>Наталья</strong>, я начинающий аналитик данных. 

В этом репозитории вы можете найти некоторые из моих проектов, выполненных во время обучения и практики.<br>

## Навыки и технологии
- Инструменты анализа данных: ``SQL``, ``Excel``: 
- Языки программирования и библиотеки: ``Python``, ``Pandas``, ``math`` 
- Системы управления базами данных: ``MySQL``, ``PostgreSQL``
- Средства визуализации данных: ``PowerBi``, ``Matplotlib``, ``seaborn``
- Инструменты для машинного обучения: ``scikit-learn``, ``TensorFlow``



## Проекты
<p> <h3><strong>Проект 1: Калькулятор юнит-экономики онлайн-школы</strong></h3></p>
<ol>
  <p><em><strong>Задача №1:</strong></em>
  Настроить в калькуляторе учет корректировок планов маркетинга.<p>
  <p><em><strong>Задача №2:</strong></em>
  Пересчитать план найма преподавателей.<p>
</ol>
  <em><strong>Решение задачи №1:</strong></em><p>
  1. Произведена обработка и агрегация данных. На их основе был собран калькулятор юнит экономики за фактический период с основными расчетными показателями. Через столбец "Изменение" реализована возможность пересчета данных с учетом плана маркетинга. Настроена взаимосвязь с листом "План маркетинга". <p>
  2. В список параметров калькулятора добавлен показатель "Поправочный коэф-т на привлечение" для корректировки существующего плана маркетинга с автоматическим пересчетом основных расчетных показателей юнит экономики. Настроен динамический расчет количества новых студентов с учетом на поправочный коэффициент.<p>
  3. Визуализированы основные показатели юнит экономики (САС, Fixed СOGS, ЗП учителей%, Маржа) за фактический период и за планируемый период. При изменении показателей визуализация изменяется автоматически.<p>



  <em><strong>Решение задачи №2:</strong></em><p>
1. Произведена обработка и агрегация данных по преподавателям за анализируемый период. Посчитаны средние показатели пропускной способности преподавателей и среднего Retention преподавателей за данный период.<p> 
2. Сделан калькулятор Найма преподавателей с возможностью изменять входные параметры: Пропускную способность преподавателей и Retention преподавателей. Через столбец "Изменение" реализована возможность пересчета данных с учетом плана найма преподавателей.<p>
3. С помощью Поиска решений составлен новый план найма преподователей с ограничением: за месяц нельзя нанять более 70 преподавателей.
4. В расчёте общей пропускной способности сделана поправка, что новые преподаватели в первый месяц своей работы могут проводить только половину уроков от средней пропускной способности преподавателя, задаваемой параметром.<p>
5. Обновлено прогнозное количество уроков, с учетом новых значений из Задачи №1 (полученные после поправки на планы маркетинга).<p>
6. Просчитан сценарий, при котором Пропускная способность преподавателей увеличится на 15 процентов, а Retention преподавателей упадёт на 2 процента.<p>
7. Визуализирован обновленный план найма преподавателей на графике.<p>
  <p><em><strong>Итог №1:</strong></em> Готовый калькулятор юнит-экономики онлайн-школы для расчета основных показателей с визуализацией роста количества студентов и выручки.
  <p><em><strong>Итог №2:</strong></em> Обновлённый план по найму - с количеством новых преподавателей по месяцам за период с 05.2021 по 04.2022
</ol>
<br> 
> <a href="https://github.com/Tashka1225/my_portfolio/blob/main/%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82%20_1_%20%D0%9A%D0%B0%D0%BB%D1%8C%D0%BA%D1%83%D0%BB%D1%8F%D1%82%D0%BE%D1%80%20%D1%8E%D0%BD%D0%B8%D1%82-%D1%8D%D0%BA%D0%BE%D0%BD%D0%BE%D0%BC%D0%B8%D0%BA%D0%B8%20%D0%BE%D0%BD%D0%BB%D0%B0%D0%B9%D0%BD-%D1%88%D0%BA%D0%BE%D0%BB%D1%8B.xlsx">Ссылка на проект №1: Калькулятор юнит-эконимики онлайн-школы</a>
  


<p><h3><strong>Проект 2: Калькулятор юнит-экономики онлайн-кинотеатра</strong></h3></p>
<ol>
  <p><em><strong>Задача №1:</strong></em> Решить задачи, связанные с исследованием аудитории и расчетов метрик, которые помогут оценить динамику изменения просмотров на платформе онлайн-кинотеатра. На основе анализа предоставленных данных ответить на вопрос, какая динамика пользовательской активности на платформе онлайн-кинотеатра.<p> 
  <p><em><strong>Задача №2:</strong></em>
  Собрать калькулятор юнит-экономики онлайн-кинотеатра. Посчитать юнит-экономику онлайн-кинотеатра. Предложить сценарий по настройке параметров для выхода на 25-процентную маржинальность.<p>   
  <p><em><strong>Задача №3:</strong></em> Презентовать новую бизнес-модель работы онлайн-кинотеатра, где будет показано, кто, где и в каком объеме смотрит фильмы на платформе. Ответить на вопрос: насколько используемая бизнес-модель эффективна с точки зрения финансовой составляющей?<p>
  </ol>
<br>
  <em><strong>Решение задачи №1:</strong></em> <p>
   1. Решены задачи, связанные с исследованием аудитории и расчетов метрик, которые помогут оценить динамику изменения просмотров на платформе онлайн-кинотеатра.
  Для понимания картины рассчитаны следующие метрики:
<ul>
    <li>- Кол-во подписок в каждый месяц       
    <li>- Кол-во просмотров в каждый месяц  
    <li>- Кол-во уникальных просматривающих пользователей в каждый месяц
    <li>- Дата первого просмотра для каждого юзера
    <li>- Кол-во первых просмотров для пользователя в каждый месяц
    <li> - Среднее кол-во просмотров на одного юзера в каждом месяце<p> </ul>

</ul> 
<br>
   <em><strong>Решение задачи №2:</strong></em> <p>
1. Для создания калькулятора юнит-экономики онлайн-кинотеатра рассчитаны следующие метрики:
<ul>
    <li>- Количество повторных оплат в каждом месяце       
    <li>- Retention для каждого месяца  
    <li>- Среднее геометрическое Retention
    <li>- Лайфтайм
    <li>- LTR
    <li>- CAC
    <li>- Маржинальность <p>
  </ul>
 2. При изменении показателей в калькуляторе был предложен сценарий по настройке параметров для выхода на 25-процентную маржинальность.<p>
  </ul>
  <br>
<em><strong>Решение задачи №3:</strong></em> <p> 
1. Для оформления презентации были построены графики:
  <ul>
    <li>- график 1: количество пользователей и интенсивность просмотров
    <li>- график 2: пользовательский Retention
    <li>- график 3: распределение просмотров по суточным часам (0-23) в разрезе будние-выходные
    <li>- график 4: распределение просмотров по тайтлам
   </ul>
<p><em><strong>Итог №1:</strong></em> Показана визуализация основных метрик, на основе которых сделан вывод по динамике пользовательской активности.<p>   
<p><em><strong>Итог №2:</strong></em> Собран калькулятор юнит-экономики на отдельном листе.<p>
<p><em><strong>Итог №3:</strong></em> Оформлена презентация с основными проанализированными метриками. На основе проведенного анализа предоставленных данных сделан вывод о том, насколько эффективна используемая бизнес-модель онлайн-кинотеатра с точки зрения финансовой составляющей.
 
</ol>
<br> 
> <a 
href="https://docs.google.com/spreadsheets/d/1v1AowF0zste1evkczrXOjH8ke4BcKNTF/edit?usp=sharing&ouid=107558701387849640195&rtpof=true&sd=true](https://drive.google.com/drive/u/2/my-drive">Ссылка на проект №2: Калькулятор юнит-эконимики онлайн-кинотеатра</a>
<br> 
<p> <h3><strong>Проект 3: Когортный анализ онлайн-кинотеатра с помощью SQL</strong></h3></p>
<ol>
  <p><em><strong>Задача №1:</strong></em> С помощью SQL решить задачи по исследованию количества первых покупок клиентов онлайн-кинотеатра в разрезе каналов привлечения и партнеров. Скачать результаты в Excel, сделать Stacked Bar Chart с распределением количества покупок по каналам привлечения и партнерам. К графику добавить срез, на котором можно выбрать, на каких по счету покупках в рамках клиента построена гистограмма.
  <p><em><strong>Задача №2:</strong></em> Дополнить код запроса SQL из Задачи №1 таким образом, чтобы получились винтажные доходимости клиентов для каждого партнера. Вывести полученные результаты в Excel, сделать визуализацию.<p>
  </ol>
<br>
  <em><strong>Решение задачи №1:</strong></em> <p>
1. Сделан запрос в базе Metabase с написанием кода, где произведена агрегация данных в соответствии с заданием.<p>
2. Результаты запроса выгружены в Excel. По выгруженным данным собрана таблица, показывающая распределение количества покупок по каналам привлечения клиентов и партнерам.<p>
3. Построена гистограмма Stacked Bar Chart, добавлен срез, на котором можно выбрать, на каких по счету покупках в рамках клиента построена гистограмма.<p>
  <em><strong>Решение задачи №2:</strong></em><p>
1. Дополнен код запроса из Задачи №1 расчетом винтажных доходимостей клиентов по партнерам.<p>
2. Результат запроса выгружен в Excel. Сделана визуализация.<p>
  
<p><em><strong>Итог №1:</strong></em> Собраны и проанализированы данные по распределению количества покупок клиентов онлайн-кинотеатра по каналам привлечения и партнерам.<p>
<p><em><strong>Итог №2:</strong></em> Рассчитаны винтажные доходимости клиентов для каждого партнера. Результат показан на графике.
  
> <a href="https://drive.google.com/drive/folders/1wdD-mfSeIsHWgrMLJz8Tv_ClAuP_EAOQ?usp=sharing">Ссылка на проект</a>
(ссылка должна содержать демонстративные материалы: скриншоты, таблички, запросы, код. Работодатель должен иметь возможность быстро посмотреть результаты работы)

  <p>Выводы (итоги):<p>
<ol>
  <li>Итог №1</li>
  <li>Итог №2</li>
</ol>

<br> 
<p> <h3><strong>Проект 4: Построение витрины для модели машинного обучения в банке </strong></h3></p> 
<ol>
  <p><em><strong>Задача №1:</strong></em>
  <p><em><strong>Задача №2:</strong></em>
</ol>  
<p>Как решала(-а): краткое описание решения (автореферат)<p>

> <a href="https://drive.google.com/drive/folders/1QOk5AAh6x7jK_yHgfKI2sUFYR7AWUi5u">Ссылка на проект</a>
(ссылка должна содержать демонстративные материалы: скриншоты, таблички, запросы, код. Работодатель должен иметь возможность быстро посмотреть результаты работы)
  
 <p>Выводы (итоги):<p>
<ol>
  <li>Итог №1</li>
  <li>Итог №2</li>
</ol>
<br> 


<p> <h3><strong>Проект 5: Моделирование изменения балансов студентов</strong></h3></p>
<ol>
  <p><em><strong>Задача №1:</strong></em>
  <p><em><strong>Задача №2:</strong></em>
</ol>

<p>Как решала(-а): краткое описание решения (автореферат)<p>

> <a href="https://github.com/Skyproportfolio/data-analytics-5month/blob/main/Проект%205.xlsx">Ссылка на проект</a>
(ссылка должна содержать демонстративные материалы: скриншоты, таблички, запросы, код. Работодатель должен иметь возможность быстро посмотреть результаты работы)
 
 <p>Выводы (итоги):<p>
<ol>
  <li>Итог №1</li>
  <li>Итог №2</li>
</ol>

## Контактная информация
- Email: Natalia.Mikhailova@gmail.com

