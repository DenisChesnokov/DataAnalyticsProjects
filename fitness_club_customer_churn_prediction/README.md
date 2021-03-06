# Анализ данных и подготовка рекомендаций по удержанию клиентов финтнес центра

Проект направлен на уменьшение оттока посетителей фитнес клуба. В проекте исследованы обезличенные данные подгоовленые отделом по работе с клиентами. На основе этих данных построена модель прогнозирования события оттока для каждого клиента. Так же проведена кластеризация - выделение групп потребителей со специфичискими признаками и выявлены группы с наибольшим процентом оттока. На основании этого разделения для групп с большим процентом оттока даны рекомендации по удержанию клиентов.

<b>Описание набора данных</b>
- gender — пол;
- Near_Location — проживание или работа в районе, где находится фитнес-центр;
- Partner — сотрудник компании-партнёра клуба (сотрудничество с компаниями, чьи сотрудники могут получать скидки на абонемент — в таком случае фитнес-центр хранит информацию о работодателе клиента);
- Promo_friends — факт первоначальной записи в рамках акции «приведи друга» (использовал промо-код от знакомого при оплате первого абонемента);
- Phone — наличие контактного телефона;
- Age — возраст;
- Lifetime — время с момента первого обращения в фитнес-центр (в месяцах).
- Contract_period — длительность текущего действующего абонемента (месяц, 6 месяцев, год);
- Month_to_end_contract — срок до окончания текущего действующего абонемента (в месяцах);
- Group_visits — факт посещения групповых занятий;
- Avg_class_frequency_total — средняя частота посещений в неделю за все время с начала действия абонемента;
- Avg_class_frequency_current_month — средняя частота посещений в неделю за предыдущий месяц;
- Avg_additional_charges_total — суммарная выручка от других услуг фитнес-центра: кафе, спорттовары, косметический и массажный салон.
- Churn — факт оттока в текущем месяце.

<b>Используемые технологии и библиотеки</b>
* Python
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn
* машинное обучение
* классификация
* кластеризация