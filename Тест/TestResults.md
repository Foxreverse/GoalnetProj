# Представление результатов

| ID | Назначение/название | Сценарий | Ожидаемый результат | Фактический результат | Оценка |
|:---:|:---:|:---|:---|:---|:---|
| 1 | Загрузка матчей при отсутствии подключения к интернету | 1. Проверьте отсутствие подключения к интернету. 2. Запустите приложение. 3. Войдите в приложение, используя свою учётную запись. | Появилось окно с сообщением отсутствия подключения к интернету. | Появилось окно с сообщениям отсутствия подключения к интернету и выбор действий | Тест пройден |
| 2 | Загрузка матчей при подключении к интернету после его отсутствия | 1. Выполните сценарий 1. 2. Подключитесь к сети интернет. 3. Нажмите кнопку "ОК" в окне с сообщением. | Отображение матчей | Началась загрузка матчей. Матчи отобразились в таблице раздела. Матчи загрузились |  Тест пройден |
| 3 | Закрытие приложения после отказа от повторной попытки загрузить матчи | 1. Выполните сценарий 1. 2. Нажмите кнопку "Отмена". | Закрытие приложения | Приложение закрылось. | Тест пройден |
| 4 | Загрузка матчей после входа в приложение при наличии подключения к интернету | 1. Проверьте наличие подключения к интернету. 2. Запустите приложение. 3. Войдите в приложение, используя свою учётную запись. Выберите раздел "Матчи". | Отображение матчей | Началась загрузка матчей. Матчи отобразились в таблице главного окна. Матчи загрузились | Тест пройден |
| 5 | Доступ к окну настройки профиля | 1. Выполните сценарий 4. 2. Нажмите "Настройки" | Появилось окно настроек профиля пользователя. | Появилось окно настроек профиля пользователя | Тест пройден |
| 6 | Добавление даты в календаре | 1. Перейдите в раздел "Kалендарь" . 2. Нажмите на дату в области календарь. 3.  В появившемся окне подтвердите выбор. | Подтверждение изменений | Подтверждение даты и переход на главный экран |Тест пройден |
| 7 | Просмотр краткой информации о матче | 1. Выполните сценарий 4. 2. После отображения матчей в таблице, кликните по любому из них один раз. | Отображение характеристик |В области "Доп. сведения" главного окна приложения отобразились основные характеристики. | Тест пройден |
| 8 | Просмотр подробной информации о матче | 1. Выполните сценарий 4. 2. После отображения матчей в таблице, кликните по любой из них два раза. | Открылась вкладка браузера. | Открылась новая вкладка браузера, установленного в системе по умолчанию, соответствующая данному матчу | Тест пройден |
| 9 | Просмотр последних трансферов | 1. Перейдите в раздел "Последние трансферы". 2. После отображения трансферов в таблице, кликните по любому из них один раз. | Отображение характеристик | В области "Доп. сведения" главного окна приложения отобразились основные характеристики. | Тест пройден |
|  |  |  |  |  |  |



