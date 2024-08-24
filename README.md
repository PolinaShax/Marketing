# Marketing

**Описание**  
Интернет-магазин собирает историю покупателей, проводит рассылки предложений и
планирует будущие продажи. Для оптимизации процессов надо выделить пользователей,
которые готовы совершить покупку в ближайшее время.

**Цель**  
Предсказать вероятность покупки в течение 90 дней

**Задачи**

Изучить данные  
Разработать полезные признаки  
Создать модель для классификации пользователей  
Улучшить модель и максимизировать метрику roc_auc  
Выполнить тестирование  

**Данные**

apparel-purchases  
история покупок  
client_id идентификатор пользователя  
quantity количество товаров в заказе  
price цена товара  
category_ids вложенные категории, к которым отнсится товар  
date дата покупки  
message_id идентификатор сообщения из рассылки  

apparel-messages  
история рекламных рассылок  
bulk_campaign_id идентификатор рекламной кампании  
client_id идентификатор пользователя  
message_id идентификатор сообщений  
event тип действия  
channel канал рассылки  
date дата рассылки  
created_at точное время создания сообщения  

apparel-target_binary  
совершит ли клиент покупку в течение следующих 90 дней   
client_id идентификатор пользователя  
target целевой признак
