# Kompashka-app

для инициализации проекта из исходников:

1. установить node.js
2. через командную строку установить:
2.1. npm install electron
2.2. npm install electron-forge
3. далее из директории проекта (cd директория) запустить:
3.1. npm start - просмотр приложения при отладке
3.2. npm run package - установка на локальном устройстве
3.3. npm run make - запуск упаковщика в установочник
_____
# Сделать рабочу трасеровку на linux
Для этого надо поставить на VM Ubuntu 20.04, в исходники проекта скачать пакет для трасеровки и упаковать его в файл формата *\*.bin*. Работать должно так: отправляется команда в консоль на трасеровку, если вылезает ошибка (а она возможна в случае, если нет пакета трасеровки), то выполняется запуск пакета из файла XXX.bin и повторяется выполнение команды.

# Сделать двухфакторную аунтентификацию 
Использовать БД SQLite или иную, если найдете.
1. Создать в БД сразу пользователя admin:admin.
2. После ввода логина и пароля долнжо запрашивать код, который действителен 10-15 секунд. Коды генерируются сервисом для двухфакторной аутентификации.


