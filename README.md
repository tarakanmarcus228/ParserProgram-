# ParserProgram-  tg:MarcusITs
Писать в телеграм для более детальной информации по данной программе и для её покупки.
Программа предназначена для автоматического сканирования веб-страниц в браузере на наличие определенных слов или фраз, которые называются "триггерами". Она представляет собой десктопное приложение, построенное на основе фреймворка PyQt5 для создания пользовательского интерфейса и использует Selenium для управления браузером.

Основные функции программы:

1.Поиск триггеров:

- Программа открывает браузер с использованием undetected_chromedriver, что позволяет избежать детектирования автоматизации.

- На каждой открытой вкладке браузера программа сканирует текст страницы и текст в чатах (например, на YouTube) на наличие заданных триггеров.

- При обнаружении триггера программа выделяет его на странице и воспроизводит звуковое уведомление.

2.Управление триггерами:

- Программа хранит триггеры в базе данных SQLite. Пользователь может добавлять новые триггеры через интерфейс.

- Программа позволяет добавлять, обновлять и просматривать список триггеров.

3.Ведение логов:

- Все найденные триггеры записываются в файл result.txt с указанием URL сайта и домена, на котором был найден триггер.

- Логи сохраняются в папке info.

4.Управление браузером:

- Пользователь может запускать и останавливать сканирование, а также открывать новые окна браузера через интерфейс программы.

- Программа предоставляет возможность паузы и возобновления сканирования, а также закрытия браузера.

5.Управление файлами:

- Пользователь может открыть файл с логами или очистить его содержимое через интерфейс программы.

Итог :
Программа будет полезна для мониторинга веб-страниц на наличие определенной информации или ключевых слов, что может применяться в различных задачах, таких как контентный мониторинг, анализ поведения пользователей в чате или отслеживание активности на веб-ресурсах.
