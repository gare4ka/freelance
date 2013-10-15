Требованию к дизайн-макетам
===========================

* Макет должен быть представлен в форматах PSD или TIFF, цветовое пространство RGB
* В рамкак макета должна быть соблюдена сетка
* Rulers должны быть выровнены точностью до одного пикселя. Полпикселя не допустимо
* В случае фиксированного шаблона должно быть четкое соответствие ширины макета утвержденной минимальной ширине сайта
* При разработке дизайна «под разрешение» обязательно отрисовывать в разрешение окна браузера, а не монитора (при 1024 пкс ширина браузера 1000 пкс)
* Обязательно наличие отдельного макета, в котором представлено оформления стандартных элементов типографики веб-страницы (заголовки, параграфы, таблицы, списки, блоки цитаты)
* Для интерактивных элементов (кнопки, ссылки и т.д.) необходимо отрисовывать все состояния:
  * idle
  * hover - при наведении
  * click - при нажатии
  * active - вы выделении (желательно)

Слои (layers)
-------------
* Каждый элемент должен находится в одном слое, названным человечески-понятным именем, а не «slice 1,2».
* Все слои одного логического элемента должны быть в одной папке (например, модуль авторизации)
* Если применяется градиент к слою, использовать обычный режим наложения (blend Mode: normal) и его реальные цвета
* Не должно быть никаких полупрозрачных градиентов и сложных режимов наложения типа «multiply, screen, overlay, и т.д.»
* Нельзя использовать сложные режимы наложения (blend mode) на любых свойствах слоя (типа inner shadow, drop shadow и т.д.)
* Нежелательно использовать «слой на слое» для создание различных эффектов (например градиента)
* Нежелательно использовать градиентные границы (border, stroke)

Текст
-----
* Для текстовых элементов обязательно указывать шрифт и его размер
* Размеры шрифтов должны быть целыми. Использование 14.22 в качестве размера шрифта недопустимо
* Обязательно прикладывать к макету шрифты, которые были использованы в макете, в формате TTF, OTF
* Шрифт должен быть бесплатным или должна быть приобретена лицензия на его использование 
* Недопустимо использовать прозрачность для элементов содержащих текст
* Желательно не использовать в макете больше 2-х не стандартных шрифтов, их количествово сильно влияет на рендеринг страницы в браузере
* Желательно все текстовые элементы делать без сглаживания