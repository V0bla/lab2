# Второе домашнее задание
## Что нужно сделать
1. добавить в Vagrantfile еще дисков;
1. собрать R0/R5/R10 на выбор;
1. прописать собранный рейд в конф, чтобы рейд собирался при загрузке;
## На проверку отправить
1. измененный Vagrantfile,
1. скрипт для создания рейда,
1. конф для автосборки рейда при загрузке.
## Решение
1. В Vagrant файл добавлены диски 5 и 6.
1. Vagrantfile, сразу собирает систему с подключенным рейдом и смонтированными разделами.
1. После перезагрузки стенда разделы автоматически монтируются.