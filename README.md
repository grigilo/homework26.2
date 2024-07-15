# 26.2. Celery

_____

### Основное задание

* Настройте проект для работы с Celery. Также настройте приложение на работу с celery-beat для выполнения периодических задач.

* Ранее вы реализовали функционал подписки на обновление курсов. Теперь добавьте асинхронную рассылку писем 
пользователям об обновлении материалов курса.

* С помощью celery-beat реализуйте фоновую задачу, которая будет проверять пользователей по дате последнего входа по полю 
last_login
 и, если пользователь не заходил более месяца, блокировать его с помощью флага 
is_active.


_____

###     * Дополнительное задание


______

### Критерии выполнения заданий

* Результат задания залили в github.com и сдали в виде ссылки на репозиторий.

______