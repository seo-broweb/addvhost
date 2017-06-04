# addvhost
Баш скрипт для автоматизация добавления нового сайт в локальное окружение.
Что делает:
1) Создаёт новую папку для проекта
2) Выставляет права
3) Добавлет index-файл для теста
4) Создаёт новый виртуальный хост с адресом сайта
5) Добавляет правило для нового домена в hosts
6) По желанию создаёт бд-mysql и нового пользователя к ней.

# Добавление скрипта в папку пользователя 
cd ~ && touch 'addvhost' && chmod +x addvhost
# Вызов скрипта
./addvhost
