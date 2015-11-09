# hmb
Home Media Bank. Storage and control center for phots and video.

Orig.: https://docs.google.com/document/d/1pf54X6wSeVQabhnvb8Wp-m2bLvNXUhW0kkRhs-mAfKU/edit?usp=sharing

Нужна тулза

Или найти, или сам. Десктоп или андроид. Организация или синхронизация файлов, поиск дубликатов с выбором решения, импорт с разделением по типу содержимого (mime?) Название: filecollection, filecraft, filelibrary, mediabank, и т.д.

home media storage, home media bank.

Требования к функционалу:
Поддержка нескольких фотоархивов (напр: все фотографии, избранные, личные и т.д.)
Сортировка и поиск фотографий.
Рейтинг фотографий (в 5 звёзд, тогда и фотоархив “избранные” не понадобится).
Импорт фотографий (по дате съёмки).
Импорт старых отсканированных фотографий (присваивать дату?).
Учёт дубликатов при импорте (MD5).
Возможность исправления параметров импорта (напр. если отсканированные фотографии были импортированы в режиме “по дате фотографии”).
Просмотр в полноэкранном режиме, слайд-шоу.
Быстрое присваивание тегов изображениям. Например при импорте.
Групповые операции со снимками: переименование, назначение ключевых слов, изменение размера, отправка по электронной почте.
Поворот изображений (по возможности без потери качества).
Exif информация о файле.
Поиск дубликатов в фотоархиве.
Распознавание лиц.
Хранение метаданных в фотографиях. По возможности.
Хранение метаданных в БД (для быстрого поиска). Контроль актуальности данных в БД.
Хранение контрольных сумм файлов (MD5).
Организовать фотобанк не в виде дерева (YYYY[/MM[/DD]][/Event]), а в виде списка YYYY[-MM[-DD]][-Event]. При импорте в каталог с существующим названием предлагать или импортировать в него же, или присвоить имя события. Причём сразу присваивать тег = <Event>.
Время съёмки, как тег при поиске.
Хранить дату импорта (напр. для последующего присваивания тегов).


Примеры организации фотобанка

Сортирую фотографии вручную по папкам (год-месяц-событие).

Для каталогизации фотографий в RAW использую Lightroom, для JPEG — Picasa.

Архив порядка 1 ТБ, но туда входят raw-оригиналы всех фотографий (я считаю, что удалять их нельзя — даже неудачные, дубли, или результаты экспериментов). Хранятся исключительно как дерево папок (год/год_квартал/год_месяц_день_событие). В некоторых случаях в пределах «года» выделяются большие подтемы («щенки», «отпуск»). Для глобального просмотра — только Пикаса. Когда-то пытался проставлять теги и делать геопривязку для всех jpeg-снимков, потом бросил — это оказалось безнадёжным делом.

И как расстроился, когда он (как и большинство менеджеров) начал неприятно притормаживать при открытии/пролистывании «тяжелых» снимков > 3 Мб.
Редкий менеджер умеет «на лету» открыть изображение, при этом сделав пре-кэширование соседних… Хотя задача-то совсем не сложная, но очень полезная.

Примеры

http://habrahabr.ru/post/165899/
http://geektimes.ru/post/115818/
http://www.exler.ru/blog/item/16522/
