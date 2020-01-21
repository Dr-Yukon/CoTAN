# CoTAN
Comic Translator by Applicated Notes

Тестовая страница https://comicslate.org/ru/playground/place03?do=edit<br />
Иного онлайн-механизма тестирования нет, кроме консоли браузера<br />
**_Проблемные места подчёркнуты_**

ОПИСАНИЕ: JS-cкрипт, подгружаемый в окно редактора из ссылки, прописанной прямо в html-код. **_Собирает HTML-код, начиная с запускающей фиолетовой кнопки "CoTAN"_**, обвешивает его сценариями. **_Стал довольно увесист, больше 40 кб_**<br />
Помогает размечать мышью координаты скриптовых наклеек на изображениях из веб-комиксов для перевода, тиражируемого на разные мировые языки. Онлайновый фотошоп, специализированный под комиксы

UI: 4 табовых режима:
- Оригинал (спрятать все нижеперечисленные наработки)
- Маски (разместить цветовые фоны поверх текстов в бабблах оригинала; **_цветовыбиратель не реализован_**)
- Тексты (спрятать рамки фонов, разместить на них наклейки с настраиваемым текстом перевода; проводит **_повторный рендер_** стилевых тегов (цвет, размер, шрифт), используемых в остальном сайте)
- Осмотр (для определения косяков)

ПЛАНЫ РАЗВИТИЯ:
- **Приоритет 9** Вставить Colorpicker (цветовыбиратель) в режим Маски
- **Приоритет 8** Попробовать не встраивать кнопку скрипта под окно, а применить скрипт к ординарному режиму просмотра, где компиляцией кода занимается сам движок - это избавило бы от повторного рендеринга, список которого в будущем определённо будет расширяться и расширяться
- **Приоритет 5** Вырвать сборку html-кода, переложить в отдельный html-файл
