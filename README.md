# JsCssManipulate. Плагин Joomla для манипуляции с Javascript и Stylesheet
Плагин позволяет удалять, перемещать в конец страницы, добавлять атрибуты defer и async скриптам, а так-же удалять или перемещать вниз страницы таблицы стилей.
#№ Синтаксис исключений для удаления скриптов и стилей
В исключения пишутся параметры REQUEST и их значения. 

Разделитель параметр/значение = (знак равно).

Разделитель между параметрами & (амперсанд).

Значений может быть несколко, разделитель значений , (запятая).

Пример option=com_content&view=article,category&catid=1,2,3,4,5

Логика обработки этой строки - "И" то есть option=com_content и view=(article или category) и catid=(1 или 2 или 3 или 4 или 5)
