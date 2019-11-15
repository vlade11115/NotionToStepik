#  Notion 2 Stepik парсит страничку на Notion и добавляет шаги на Stepik!

Это скрипт, который превращает содержимое Notion страницв в шаги на степике, чтобы вы могли использовать самый удобный блокнот и самую лучшую платформу для создания курсов вместе!

## Как использоыать

* Откройте файл notion2stepik, скопируйте в него адрес странички в ноушне и номер урока на степике
* Запустите скрипт: `python3 notion2stepik.py`
* Следуйте инструкциям скрипта

## Что уже сделано?

Текстовые блоки превращаются в параграфы
Заголовки 1 и 2 уровня превращаются в заголовки
Горизонтальные разделители разделяют контент на степы
Все списки превращаются в неупорядоченные списки
Блоки кода превращаются в блоки кода (хтмл экранируется!)

## Что еще НЕ сделано?

Картинки не загружаются (у Stepik нет API, ищем выход)
Встроенные штуки, типа карт и видео теряются
Полужирное и курсивное форматирование теряется
Графического интерфейса нет

