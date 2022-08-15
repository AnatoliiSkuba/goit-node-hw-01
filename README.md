Запускаем команды в терминале и делаем отдельный скриншот результата выполнения каждой команды.

# Получаем и выводим весь список контактов в виде таблицы (console.table)

node index.js --action list

http://joxi.net/823MBbeiwnQbWr

# Получаем контакт по id

node index.js --action get --id 5

http://joxi.net/BA0JEMeTql88qm

# Добавялем контакт

node index.js --action add --name Mango --email mango@gmail.com --phone 322-22-22

http://joxi.net/VrwDv3acgVGGzm

# Удаляем контакт

node index.js --action remove --id=3

http://joxi.net/DmB5Bneu6dkklr
