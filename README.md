# Проргаммирование. Введение в профессию (А.В.Столяров)
## Том 1. Азы программирования

**Предисловие первое, философское**

- Главная цель написания книги: раздать электронную версию книги бесплатно (сохраняя авторские права)
- Я раньше писал книги не более 200 стр
- Чтобы написать данную книгу было запланировано 6 месяцев и 600 тысяч рублей
- C 01-01-2015 [краудфандингом](https://ru.wikipedia.org/wiki/%D0%9A%D1%80%D0%B0%D1%83%D0%B4%D1%84%D0%B0%D0%BD%D0%B4%D0%B8%D0%BD%D0%B3) собрал больше 120000 рублей (минимальная сумма, с которой начал работу)
- 11-2015 завершил то, что было запланировано, но много чего надо было добавить: найти дизайнера книги, собрать деньги на издание.
- Было решено разделить книгу на три тома 
- 03-2016 **первый том** пошел на издание (уже пожертвовано 400 тыс, потрачено 557 часов чистой работы)
- 06-2016 **второй том** пошел в печать, но проект ушел в минус 190 тысяч (в 09-2016 вышел из минуса)
- 06-2017 **третий том** пошел в печать (в минусе 117 тысяч, 975 часов общее время)
- 03-2020 **четвертый том** (короновирусная паника на дворе, общее время 1703 часа из которых 728 на 4-ый том, пожертвовано 1173798 рублей)
- 02-2021 _второе издание_ закончено (2200 часов, 500ч на второе издание, 1750000 р собрано, но в конце пошли в минус)
- Цель достигнута: победа над копирайтерами

**Предусловие второе, методическое**

_Можно ли выучить программиста_
- Сейчас у программистов ЗП высокая, профессия востребованная, но всё же трудно найти хорошего специалиста
- Фактически программированию нигде не учат. Мало преподавателей имеют опыт реального программирования
- **Программисты - изрядные извращенцы, поскольку ухитряются получить удовольствие от работы, от которой любой нормальный человек бежал бы без оглядки**.
- В ВУЗах сложно создать программиста - оно дается от мастера к ученику в деле
- Стать программистом человек может только и исключительно в результате самообучения

_Самообучение - это тоже не так просто_
- Плохо начинать изучение с событийно-ориентированного программирования (кликами создать создать окна и формы, как в готовых фреймворках)
- Те, кто начинают с веб-разработки там же и заканчивают. Разница между скриптами и серьезными приложениями можно сравнить различием между мопедом и карьерным самосвалом

_Выход есть, или «Почему Unix»_
- Коротко: командная строка быстрее чем иконкокликание в 10 раз

**_Причина первая - математическая_**
- Командная строка соотвутствует формуле: входные данные - обработка - выход
- Поскольку текстовое представление универсально, алгебра консольных программ - средство мощное с широким диапазоном решаемых задач

**_Причина вторая - психологическая_**
- Ремесло (программирование) _выучить_ нельзя, можно только _научиться_ следующими шагами:
1 - решить придуманное задание (интересное)
2 - рушить реальну (пусть простую) задачу
3 - появление ценителей ваших решений (те, кто используя ваше решение сэкономил себе время)
- Обучать на Windows (без терминала имеется ввиду) - лишить человека выполнить все три пункта (не оконные программы а текстовые)
- Использовать надо исключительно Unix систему

**_Причина третья - эргономическая_**
- Юзабилити у терминала больше, чем у окон

**_Причина четвертая - педагогическая_**
_Язык определяет мышление_
- Си и С++ как первый язык - этл плохой подход
- К изучению Си надо подходить уже понимая указатели и умея с ними обращаться
- Начиная с Си можно получить «сишность головного мозга»
- Для начала лучше всего изучать на Паскале, так как многие темы программирование реализумые на нём (те же указатели)
- Если Паскаль использовать для подготовки к переходу на Си, то можно исключить темы _тип-множество_, _оператор with_ и _вложенные подпрограммы_
- В Паскале нет проблемы «побочных эффектов» Си и "присвоение" здесь _оператор_ а не _операция_
- После этого необходима понять базовую работу ОС, для этого подойдёт Ассемблер
- Порядок изучения должен быть следующим: 1) Паскаль 2) Ассемблер 3)Си 4)С++ (как уникальное явление) 


**Предисловие третье, напутственное**
- Люди издавна горели идеей создать что-то, что действует само по себе (автоматизация)
- До появления электричества, была только механика (механики часовщики).
- В 18 веке [Пьер Жаке Дро](https://en.wikipedia.org/wiki/Pierre_Jaquet-Droz) создал [«автоматон»](https://ru.wikipedia.org/wiki/%D0%90%D0%B2%D1%82%D0%BE%D0%BC%D0%B0%D1%82%D0%BE%D0%BD)-ы
- 1772 году «Пишущий мальчик» состоял из 6 с лишним тысяч деталей
- Одной гениальной идеей никуда не пойдёшь, нужны финансы и заинтересованные люди, в те времена с последними приходилось сложновато
- С появлением программирования стало легко и без трудностей создавать то, что задумаешь, _программа само по себе готовое издание_
- Сейчас учиться в ВУЗ-е желательно, но не обязательно
- Программистом я сделал себя сам, а не ВУЗ
- Цель книги собрать воедино необходимые знания для самостоятельного изучения, чтобы не брать всё из сомнительных источников
- Эта книга содержит общие сведения, кроме этого необходимо практиковаться 
- OC Unix должен стать вашим повседневным делом
- Стать программистом могут те, у кого есть склонность к программированию (интерес, сильное погружение, усидчивость)
- Вводная часть может занять от 1 дня до нескольких недель (Работа с ОС Unix, установка, команды)
- На написание этой книги я потратил 6 лет, надеюсь что не зря

**Структура книги и соглашения, используемые в тексте**
- ТОМ 1
- Часть 1 - история, математика (дискретная), теория вычислимости и алгоритмов, как использовать ОС юникс
- Часть 2 - Базовые навыки написания программ на Паскале (цель не Паскаль)
- Часть 3 - Низкоуровневое программирование - Ассемблер, Си


### ЧАСТЬ 1
**Предварительные сведения**
1.1. Компьютер: что это такое
- Главная функция компьютера - считать, вычислять (ныне занимается чем угодно, но не всегда вычислением)

1.1.1. Немного истории 
- В 1623 году была создана первая в истории вычислительная машина - [арифмометр Вильгельма Шиккарда «Счетные часы»](https://ru.wikipedia.org/wiki/%D0%A1%D1%87%D0%B8%D1%82%D0%B0%D1%8E%D1%89%D0%B8%D0%B5_%D1%87%D0%B0%D1%81%D1%8B_%D0%92%D0%B8%D0%BB%D1%8C%D0%B3%D0%B5%D0%BB%D1%8C%D0%BC%D0%B0_%D0%A8%D0%B8%D0%BA%D0%BA%D0%B0%D1%80%D0%B4%D0%B0)
- «Счетные часы» оперировали 6-значными целыми числами, сложение вычитание делалось, при переполнении был звонок (оригинал машины не сохранился, в 1960 году была создана копия)
- В 1645г был создан [арифмометр Блеза Паскаля](https://ru.wikipedia.org/wiki/%D0%A1%D1%83%D0%BC%D0%BC%D0%B8%D1%80%D1%83%D1%8E%D1%89%D0%B0%D1%8F_%D0%BC%D0%B0%D1%88%D0%B8%D0%BD%D0%B0_%D0%9F%D0%B0%D1%81%D0%BA%D0%B0%D0%BB%D1%8F) (начал работу над ним в 1642 году - в 19 лет, для подсчета налогов своему отцу)
- Арифмометр Паскаля работал с 5-значными (5 разрядов) числами (пример: 500 - 134 =  500 + 99866, так как нет 6-го разряда, то получаем не 100366, а 00366. _x-y = x + (100000 - y) - 100000)_
- 30 лет спустя немецкий математик Вильгельм Лейбниц Готфрид создал [механизм](https://ru.wikipedia.org/wiki/%D0%90%D1%80%D0%B8%D1%84%D0%BC%D0%BE%D0%BC%D0%B5%D1%82%D1%80_%D0%9B%D0%B5%D0%B9%D0%B1%D0%BD%D0%B8%D1%86%D0%B0) способный на +, -, х, /
- История арифмометров закончилась во второй половине 20-го века (электронные калькуляторы пришли)
- Но все еще без человека механизмы ничего не делали (промежуточные результаты выписывали сами люди)
- Английский математик Чарльз Бебидж (1792-1871) заметил, что можно автоматизировать работу расчетчиков 
- В 1822 году он предложи идею [«разностной машины»](https://ru.wikipedia.org/wiki/%D0%A0%D0%B0%D0%B7%D0%BD%D0%BE%D1%81%D1%82%D0%BD%D0%B0%D1%8F_%D0%BC%D0%B0%D1%88%D0%B8%D0%BD%D0%B0_%D0%A7%D0%B0%D1%80%D0%BB%D1%8C%D0%B7%D0%B0_%D0%91%D1%8D%D0%B1%D0%B1%D0%B8%D0%B4%D0%B6%D0%B0#:~:text=%D0%A0%D0%B0%CC%81%D0%B7%D0%BD%D0%BE%D1%81%D1%82%D0%BD%D0%B0%D1%8F%20%D0%BC%D0%B0%D1%88%D0%B8%CC%81%D0%BD%D0%B0%20%D0%A7%D0%B0%D1%80%D0%BB%D1%8C%D0%B7%D0%B0%20%D0%91%D1%8D%D0%B1%D0%B1%D0%B8%D0%B4%D0%B6%D0%B0%20%E2%80%94%20%D0%BC%D0%B5%D1%85%D0%B0%D0%BD%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B9,%D0%BC%D0%BD%D0%BE%D0%B3%D0%BE%D1%87%D0%BB%D0%B5%D0%BD%D0%B0%D0%BC%D0%B8%20%D0%B8%20%D0%B2%D1%8B%D1%87%D0%B8%D1%81%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%BA%D0%BE%D0%BD%D0%B5%D1%87%D0%BD%D1%8B%D1%85%20%D1%80%D0%B0%D0%B7%D0%BD%D0%BE%D1%81%D1%82%D0%B5%D0%B9.)
- Идею он реализовать не смог за 20 лет, очень много денег потратил и сам и государство. Не закончив оставил работу
- Основываясь на его принципах швед Георг Шутц создал рабочий экземпляр и подарил копии Британии и США
- Интереснее "разностной машины" считается "аналитическая машина" Беббиджа
- Идею "аналитической машины" он прочитал в Турине, потом итальянский математик Луиджи Менабреа опубликовал его на французском
- По просьбе Беббиджа Ада Ловлей перевела статью на английский с развернутыми комментариями и примерами, одна из которых [вычисление чисел Бернулли аналитической машиной](http://elib.osu.ru/bitstream/123456789/906/1/1252-1260.pdf).
- **Это считается первой программой в мире**
- Идея аналитической машины опередила уровень технологии на 100 лет
- Первая программируемая машина является [Z1](https://ru.wikipedia.org/wiki/Z1_(%D0%B2%D1%8B%D1%87%D0%B8%D1%81%D0%BB%D0%B8%D1%82%D0%B5%D0%BB%D1%8C%D0%BD%D0%B0%D1%8F_%D0%BC%D0%B0%D1%88%D0%B8%D0%BD%D0%B0)) (Конрад Цузе, Германия 1938г) (механический комп из более 30000 деталей). [Видео](https://www.youtube.com/watch?v=wu3Zch5tcM0)
- В машине команды команды вводились через перфоленты, не было циклов, чтение было в одну сторону
- В 1941 году он создал новую модель Z3, что имело и память и повторение, программы записывались не кинопленках
- В 1944 году создал Z4 - добавился условный оператор (ветвление)
- Во время Второй Мировой пришелся бум [электромеханических](https://ru.wikipedia.org/wiki/%D0%AD%D0%BB%D0%B5%D0%BA%D1%82%D1%80%D0%BE%D1%82%D0%B5%D1%85%D0%BD%D0%B8%D0%BA%D0%B0#%D0%AD%D0%BB%D0%B5%D0%BA%D1%82%D1%80%D0%BE%D0%BC%D0%B5%D1%85%D0%B0%D0%BD%D0%B8%D0%BA%D0%B0) и [электронных](https://ru.wikipedia.org/wiki/%D0%AD%D0%BB%D0%B5%D0%BA%D1%82%D1%80%D0%BE%D0%BD%D0%B8%D0%BA%D0%B0) устройств, основанных на [электронно-вакуумных лампах](https://ru.wikipedia.org/wiki/%D0%AD%D0%BB%D0%B5%D0%BA%D1%82%D1%80%D0%BE%D0%BD%D0%BD%D0%B0%D1%8F_%D0%BB%D0%B0%D0%BC%D0%BF%D0%B0)
- Радиолампа (электро-вакуумная) - колба с [электродами](https://ru.wikipedia.org/wiki/%D0%AD%D0%BB%D0%B5%D0%BA%D1%82%D1%80%D0%BE%D0%B4) ([анод](https://ru.wikipedia.org/wiki/%D0%90%D0%BD%D0%BE%D0%B4) и [катод](https://ru.wikipedia.org/wiki/%D0%9A%D0%B0%D1%82%D0%BE%D0%B4)), из которой откачан воздух 
- Виды радиоламп - [диод](https://ru.wikipedia.org/wiki/%D0%94%D0%B8%D0%BE%D0%B4), [триод](https://ru.wikipedia.org/wiki/%D0%A2%D1%80%D0%B8%D0%BE%D0%B4)
- [Триггер](https://ru.wikipedia.org/wiki/%D0%A2%D1%80%D0%B8%D0%B3%D0%B3%D0%B5%D1%80) - устройство полученное комбинациями триодов, имеет 2 состояния открытый и закрытый
- **Триггер можно использовать для хранение 1 бита информации**
- Другие схемы соединения триодов позволяют создать логические вентили - конъюнкция, дизъюнкция и отрицание
- Из этих элементов строили и вычислительные машины
- Из-за отсутствия механики в устройстве лампы работали быстрее, но были ненадежными (Эниак имела 18000 ламп и работала при условии исправности всех ламп)
- ENIAC - США (рассекретили и изучили), Colossus - Британия (сожгли всё, Черчилль приказал)

**Компьютеры на радиолампах - _ЭВМ-ы первого поколения_**
- К этому эпоху относится важное изобретение «принцип хранимой программы»
- Программа в виде команд хранится в той же самой памяти, что и данные.
- Память однородна и коды команд от данных ничем не отличаются
- Такие машины называют [машинами Фон Неймана](https://ru.wikipedia.org/wiki/%D0%9C%D0%B0%D1%88%D0%B8%D0%BD%D0%B0_%D1%84%D0%BE%D0%BD_%D0%9D%D0%B5%D0%B9%D0%BC%D0%B0%D0%BD%D0%B0)
- Первый комп с памятью [EDVAC](https://ru.wikipedia.org/wiki/EDVAC) 
- Компьютеры занимали целые здания, имели мало памяти

**Компьютеры на твердотельных электронных компонентах - _ЭВМ-ы второго поколения_**
- Основным прорывом стал **ПОЛУПРОВОДНИКОВЫЙ ТРАНЗИСТОР**
- В 1947 году первый рабочий [транзистор](https://ru.wikipedia.org/wiki/%D0%98%D0%B7%D0%BE%D0%B1%D1%80%D0%B5%D1%82%D0%B5%D0%BD%D0%B8%D0%B5_%D1%82%D1%80%D0%B0%D0%BD%D0%B7%D0%B8%D1%81%D1%82%D0%BE%D1%80%D0%B0) был создан в Bell Labs (Уильям Мокли, Джон Бардина, Уолтер Браттейн. Получили Нобелевскую премию по физике)
- _Разница с радиолампами_ - 1) **миниатюрность**, 2) **меньше электричества требовалось для разогрева** 3) **безотказность**
- Ещё одним серьезным изобретением стал **ПАМЯТЬ НА МАГНИТНЫХ СЕРДЕЧНИКАХ** (gрямоугольная сетка из проводов - каждый узел (ферритовое колечко) = 1 бит, заменял 3-4 радиолампы)
- Первые полностью транзисторные компьютеры были созданы 1953 году
- В 1954 году IBM выпустила [IBM 608 Transistor Calculator](https://en.wikipedia.org/wiki/IBM_608) (первый коммерческий компьютер)
- Компьютеры занимают комнату

**Компьютеры на интегральных схемах - _ЭВМ-ы третьего поколения_**
- [Интегральная схема](https://ru.wikipedia.org/wiki/%D0%98%D0%BD%D1%82%D0%B5%D0%B3%D1%80%D0%B0%D0%BB%D1%8C%D0%BD%D0%B0%D1%8F_%D1%81%D1%85%D0%B5%D0%BC%D0%B0) (полупроводниковое устройство, в котором на одном кристалле несколько (ныне несколько миллиардов) элементов (транзисторы, диоды, сопротивления, конденсаторы))
- Уже стало возможным массово выпускать компьютеры (10 тысяч единиц)  
 
**Компьютеры на микросхемах - _ЭВМ-ы четвертого поколения_**
- В 1971 году микросхемы заключали в себе весь центральный процессор целиком
- Первым микропроцессором (доступный на рынке) называют [Intel 4004](https://ru.wikipedia.org/wiki/Intel_4004)
- Появилось понятие персональный компьютер

**1.1.2. Процессор, память, шина**
_Информация идёт по **шине** в **машине (ЭВМ)**_
- Основой компьютера служит [**ОБЩАЯ ШИНА**](https://ru.wikipedia.org/wiki/%D0%A8%D0%B8%D0%BD%D0%B0_(%D1%82%D0%BE%D0%BF%D0%BE%D0%BB%D0%BE%D0%B3%D0%B8%D1%8F_%D0%BA%D0%BE%D0%BC%D0%BF%D1%8C%D1%8E%D1%82%D0%B5%D1%80%D0%BD%D0%BE%D0%B9_%D1%81%D0%B5%D1%82%D0%B8)) (представляет собой много параллельных проводов называемых ДОРОЖКАМИ)
- К **ШИНЕ** подключаются [**ЦП**](https://ru.wikipedia.org/wiki/%D0%A6%D0%B5%D0%BD%D1%82%D1%80%D0%B0%D0%BB%D1%8C%D0%BD%D1%8B%D0%B9_%D0%BF%D1%80%D0%BE%D1%86%D0%B5%D1%81%D1%81%D0%BE%D1%80) (центральный процессор CPU), [**ОЗУ**](https://ru.wikipedia.org/wiki/%D0%9E%D0%BF%D0%B5%D1%80%D0%B0%D1%82%D0%B8%D0%B2%D0%BD%D0%B0%D1%8F_%D0%BF%D0%B0%D0%BC%D1%8F%D1%82%D1%8C) (оперативное запоминающее устройство RAM) и [**КОНТРОЛЛЕРЫ**](https://en.wikipedia.org/wiki/Controller_(computing)) позволяющие управлять остальными устройствами компьютера.
- По шине ЦП взаимодействует с остальными компонентами компьютера. 
- ОЗУ и контроллеры игнорируют любую информацию из шины, кроме той, которая адресована конкретно данному банку памяти или контроллеру
- Поэтому часть дорожек шины выделяется под адрес - [**ШИНА АДРЕСОВ**](https://ru.wikipedia.org/wiki/%D0%A8%D0%B8%D0%BD%D0%B0_%D0%B0%D0%B4%D1%80%D0%B5%D1%81%D0%B0) (ША)
- Дорожка передачи информации - [**ШИНА ДАННЫХ**](https://ru.wikipedia.org/wiki/%D0%A8%D0%B8%D0%BD%D0%B0_%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85) (ШД)
- Дорожка передачи управляющих сигналов - [**ШИНА УПРАВЛЕНИЯ**](https://ru.wikipedia.org/wiki/%D0%A8%D0%B8%D0%BD%D0%B0_%D1%83%D0%BF%D1%80%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F) (ШУ)
- Каждая дорожка может находится в состоянии 1 или 0 
- Определенная комбинация нулей и единиц (0 и 1) на шине адресов составляют адрес
- Все устройства, кроме ЦП подключаются к шине по адресу (состояние шины адресов), если их адрес равен данному адресу, иначе они не взаимодействуют с этой шиной, чтобы не мешать работе ЦП с другими устройствами
- ОЗУ или просто (оперативная) память состоит из одинаковых [ячеек памяти](https://ru.wikipedia.org/wiki/%D0%AF%D1%87%D0%B5%D0%B9%D0%BA%D0%B0_%D0%BF%D0%B0%D0%BC%D1%8F%D1%82%D0%B8) (memory location, а не memory cell), каждая из которых имеет свой уникальный адрес, отличающий его от других.
- [Адресное пространство](https://ru.wikipedia.org/wiki/%D0%90%D0%B4%D1%80%D0%B5%D1%81%D0%BD%D0%BE%D0%B5_%D0%BF%D1%80%D0%BE%D1%81%D1%82%D1%80%D0%B0%D0%BD%D1%81%D1%82%D0%B2%D0%BE_(%D0%B8%D0%BD%D1%84%D0%BE%D1%80%D0%BC%D0%B0%D1%82%D0%B8%D0%BA%D0%B0)) - технически всевозможные адреса на компьютере. Его размер равен **2^N** (**N** - количество дорожек на шине адресов) 
- Операции с ячейкой памяти - **записать** значение, **прочитать** из нее значение
- Для выполнения таких операций ЦП 
1. Устанавливает адрес нужной ему ячейки памяти на ША 
2. По ШУ отправляет импульс на ячейку памяти 
3. Импульс заставляет ячейку передать в ШД свое содержимое (чтение) или, наоборот, установить свое новое содержимое в соответствии с состоянием ШД (запись). Старое содержимое ячейки теряется
- По ШД информация передается параллельно: Если ячейка имеет 8 разрядов (1 и 0-ей), то при передачи данных (чтение или запись) используется 8 дорожек ШД. При чтении ячейка памяти должна установить на этих дорожках логические уровни (1 и 0), соответствующее хранящимся в ней цифрам, а при записи, наоборот, установить хранящиеся в ячейке цифры в соответствии с логическими уровнями дорожек данных. 
- Для хранения значений часто используется несколько ячеек памяти, идущих подряд (соседний адреса), разрядности ШД хватает на одновременную передачу данных нескольких ячеек.
- Оперативная память (ОЗУ) - электронное устройств, функционирование которого зависит от электропитания
- При выключении питания информация в ячейках памяти немедленно и безвозвратно теряется
- Память компьютера != дисковые [запоминающие устройства](https://ru.wikipedia.org/wiki/%D0%97%D0%B0%D0%BF%D0%BE%D0%BC%D0%B8%D0%BD%D0%B0%D1%8E%D1%89%D0%B5%D0%B5_%D1%83%D1%81%D1%82%D1%80%D0%BE%D0%B9%D1%81%D1%82%D0%B2%D0%BE) (где хранятся файлы)
- С памятью ЦП может взаимодействовать через шину, а работать с дисками и другими устройствами ЦП сам по себе не может. Для этого на процессоре надо выполнять специальные программы - **драйверы**
- [Драйвера](https://ru.wikipedia.org/wiki/%D0%94%D1%80%D0%B0%D0%B9%D0%B2%D0%B5%D1%80) организуют работу с внешними устройствами через контроллеры путем передачи определенной управляющей информации  
- Некоторые блоки памяти физически представляют собой постоянную (не оперативную) память, которая не меняется (не поддерживает операцию записи процессором)
- При выключении информация не стирается 
- При чтении ЦП не различает постоянную и оперативную памяти
- Загрузчик операционной системы обычно записывается в постоянную память, чтобы при включении он нашел место загрузки ОС и после ее запуска отдал управление ей 
- ОС организует хранение информации на [дисках](https://ru.wikipedia.org/wiki/%D0%96%D1%91%D1%81%D1%82%D0%BA%D0%B8%D0%B9_%D0%B4%D0%B8%D1%81%D0%BA) в виде файлов (единица информационного хранения, имеющее имя)
- Файлы размещаются только на дисках
- В памяти никаких файлов нет. Распределение памяти постоянно меняется.
- Памяти никакие имена не нужны ОС идентифицирует их как ей удобно   

**1.1.3. Принцип работы ЦП**
- ЦП - электронная схема (одна микросхема). Назначение - выполнить простейшие дейтсвия, заданные [**машинными командами**](https://ru.wikipedia.org/wiki/%D0%9C%D0%B0%D1%88%D0%B8%D0%BD%D0%BD%D1%8B%D0%B9_%D0%BA%D0%BE%D0%B4)
- В составе ЦП входят регистры - запоминающие устройства, способные хранить от нескольких до нескольких десятков двоичных разрядов. Основную работу процессор производит над информацией, хранящейся в [регистрах](https://ru.wikipedia.org/wiki/%D0%A0%D0%B5%D0%B3%D0%B8%D1%81%D1%82%D1%80_%D0%BF%D1%80%D0%BE%D1%86%D0%B5%D1%81%D1%81%D0%BE%D1%80%D0%B0) (чтение или запись через шину из оперативной памяти в процессор или наоборот)  
_**Система команд:**_
- **Чтение** или **запись** 
- ЦП имеет **команды арифметики** **- +, - (в некоторых есть * и /)** _над регистрами и группами ячеек_
- **Копирование** из _одного регистра в другой _
- **Логические операции** - и, или, не...
- **Переход** к выполнению команд из другого места 
- Каждая машинная команда имеет **машинный код**
- Программа из таких машинных кодов располагается в ячейках памяти 
- Один из регистров процессора, который называется [**СЧЁТЧИК КОМАНД**](https://ru.wikipedia.org/wiki/%D0%A1%D1%87%D1%91%D1%82%D1%87%D0%B8%D0%BA_%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4) (или **УКАЗАТЕЛЬ ИНСТРУКЦИИ**) содержит адрес той ячейки, в которой располагается следующая инструкция, предназначенная к выполнению
- Процессор работает раз за разом выполняя [**ЦИКЛ ОБРАБОТКИ КОМАНД**](https://ru.wikipedia.org/wiki/%D0%9C%D0%B0%D1%88%D0%B8%D0%BD%D0%BD%D1%8B%D0%B9_%D1%86%D0%B8%D0%BA%D0%BB): 
1) Берет адрес из счетчика команд, и из ячеек памяти по этому адресу считывается код очередной команды 
2) Счетчик команд меняет свое значение так, чтобы указать на следующую команду  
3) Схемы ЦП дешифруют код и выполняют действия 
4) Возврат к пункту 1 
- Можно перенаправить выполнение в другое место с помощью [**команды перехода**](https://ru.wikipedia.org/wiki/%D0%9A%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D0%B0_%D0%BF%D0%B5%D1%80%D0%B5%D1%85%D0%BE%D0%B4%D0%B0) (условные и безусловные) 

**1.1.4. Внешние устройства** //можно пропустить
- **Теги**: общая шина, контроллеры, адреса портов ввода-вывода, драйвера

**1.1.5. Иерархия запоминающих устройств** //можно пропустить
- Теги: РЕГИСТРЫ, КЭШ, ОПЕРАТИВНАЯ ПАМЯТЬ, ДИСКИ, ЛЕНТЫ

## **1.2. Как правильно использовать компьютер**
**1.2.1. ОС-ы и виды пользовательского интерфейса**
- Существуют [ОС](https://ru.wikipedia.org/wiki/%D0%9E%D0%BF%D0%B5%D1%80%D0%B0%D1%86%D0%B8%D0%BE%D0%BD%D0%BD%D0%B0%D1%8F_%D1%81%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D0%B0)-ы: Windows (Microsoft), Unix - Linux дистрибуции - Ubuntu, Fedora, Gentoo, Debian; BSD - FreeBSD, OpenBSD; Unix - Android (на ядре Linux), Mac OS, iOS
- В Unix системах [UI](https://ru.wikipedia.org/wiki/%D0%98%D0%BD%D1%82%D0%B5%D1%80%D1%84%D0%B5%D0%B9%D1%81_%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D1%8F) и ОС раздельны, UI может поддержать обычная программа ([оконный менеджер](https://ru.wikipedia.org/wiki/%D0%9C%D0%B5%D0%BD%D0%B5%D0%B4%D0%B6%D0%B5%D1%80_%D0%BE%D0%BA%D0%BE%D0%BD)), в Windows UI записан в ядро, поэтому пользователь не может менять интерфейс по своему
- [Телетайп (tty)](https://ru.wikipedia.org/wiki/%D0%A2%D0%B5%D0%BB%D0%B5%D1%82%D0%B0%D0%B9%D0%BF) - предок [компьютерного терминала](https://ru.wikipedia.org/wiki/%D0%9A%D0%BE%D0%BC%D0%BF%D1%8C%D1%8E%D1%82%D0%B5%D1%80%D0%BD%D1%8B%D0%B9_%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D0%B0%D0%BB)
- Говорится о преимуществах командной строки перед кликанием (как в Windows)
- Для профессионала в программировании обязательно надо знать командную строку

**1.2.2. История ОС Unix**
- Конец 1960-х годов General Electrics, MIT, Bell Labs разрабатывали ОС [Multics](https://ru.wikipedia.org/wiki/Multics). 
- Bell Labs вышла из проекта, один из её сотрудников [Кен Томпсон](https://ru.wikipedia.org/wiki/%D0%A2%D0%BE%D0%BC%D0%BF%D1%81%D0%BE%D0%BD,_%D0%9A%D0%B5%D0%BD) интересовался компьютерными играми (тогда это направление только появилось)
- У Bell Labs была утаревшая машина [PDP-7](https://ru.wikipedia.org/wiki/PDP-7), которую Томпсон взял для своих работ
- Имея опыт в MULTICS написал ОС для PDP-7 - UNICS (название в шутку предложил [Брайан Керниган](https://ru.wikipedia.org/wiki/%D0%9A%D0%B5%D1%80%D0%BD%D0%B8%D0%B3%D0%B0%D0%BD,_%D0%91%D1%80%D0%B0%D0%B9%D0%B0%D0%BD), после суффикс CS было заменено на X), которая была двухзадачной в начале
- К Тому потом присоединился [Деннис Ритчи](https://ru.wikipedia.org/wiki/%D0%A0%D0%B8%D1%82%D1%87%D0%B8,_%D0%94%D0%B5%D0%BD%D0%BD%D0%B8%D1%81) и для [PDP-11](https://ru.wikipedia.org/wiki/PDP-11) они переписали ОС
- Томпсон попытался использовать усеченный диалект языка [BCPL (Basic Combined Programming Language)](https://ru.wikipedia.org/wiki/BCPL) который назвал «B», но он оказался простым - не имел даже структурных данных
- Деннис предложил расширить язык и выбрал следующую букву после «B» => [**«C»**](https://ru.wikipedia.org/wiki/%D0%A1%D0%B8_(%D1%8F%D0%B7%D1%8B%D0%BA_%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F)) (Си)
- В 1973 году на Си удалось переписать созданную систему Тома. 
- Антимонопольные ограничения не позволяли [AT&T](https://ru.wikipedia.org/wiki/AT%26T) участвовать в чем-то кроме телефонии, поэтому копии Unix с исходными текстами предоставлялись всем желающим на некоммерческой основе
- Деннис Ритчи, Стив Джонсон предложили новую архитектур, которую испробовали на [Interdata 8/32](https://en.wikipedia.org/wiki/Interdata_7/32_and_8/32). В рамках этой работы Джонсон написал переносимый компилятор языка Си
- В 1977 году перенос системы на новую архитектуру
- Важный вклад в развитие Unix внесли ребята из универстета Беркли (Berkeley Software Distribution [**BSD**](https://ru.wikipedia.org/wiki/BSD) была создана там)
- В 1984 году были сняты антимонопольные ограничения с AT&T и они начали коммерциализации Unix текстов. Было много судебных разбирательств между разработчиками Unix и AT&T
- Все было улажено в 1993 году
- Появление [Intel 80386](https://ru.wikipedia.org/wiki/Intel_80386)
- 1984г [Ричард Столлман](https://ru.wikipedia.org/wiki/%D0%A1%D1%82%D0%BE%D0%BB%D0%BB%D0%BC%D0%B0%D0%BD,_%D0%A0%D0%B8%D1%87%D0%B0%D1%80%D0%B4_%D0%9C%D1%8D%D1%82%D1%82%D1%8C%D1%8E) основал Фонд свободного программного обеспечения 
- 1991г [Линус Торвальд](https://ru.wikipedia.org/wiki/%D0%A2%D0%BE%D1%80%D0%B2%D0%B0%D0%BB%D1%8C%D0%B4%D1%81,_%D0%9B%D0%B8%D0%BD%D1%83%D1%81) (финский студенд) начал работу над ядром Unix-подобной системы для i386
- 1994 официальная версия Linux (сам Линукс хотел назвать Freax), вторая версия в 1996

**1.2.3 Unix на домашней машине**
- Отличие unix-подобных систем от «коммерческих» это то, что можно массово использовать их, не платить
- Есть два главных семейства unix - **Linux** (дистрибуции _Ubuntu, Gentoo_, ...) и **BSD** (_FreeBSD, OpenBSD, NetBSD_...)
- В этом параграфе говорится где и как установить дистрибутив Linux-а и как лучше настроить работу с ним

**1.2.4 Первый сеанс в компьютерном классе**
- В этом параграфе говорится как войти в систему и что вводить в терминал
- Для запуска оконной оболочки X Window можно запустить команду **startx**

**1.2.5 Дерево каталогов. Работа с файлами**
- В терминале, если в конце строки знак **#**, то вы зашли _как админ_, иначе будет **$**
- После вода в систему вы окажетесь в вашем **ДОМАШНЕМ КАТАЛОГ**-е (**pwd** - узнать путь, **ls** - список файлов)
- Файлы начинающиеся со знака точка - **скрытые файла** (можно посмотреть их с **ls -a** (означает **all**))
- **./** - это ссылка на _данный_ каталог, а **../** - на каталог, _содержащий данный_ каталог
- **cd** - команда перехода в каталог (по указанному пути)
- Команды **cp** (копировани), **mv** (переименование или перемещение файла), **rm** (удаление файла), **mkdir** (создание каталога), **rmdir** (удаление каталога), **touch** (создание файла или установка нового времени модификации), less (просмотр содержимого файла с пейджингом)
- **Абсолютный и относительный пути**
- _Никогда не используйте русские буквы, пробелы и знаки препинания в названии файла_

**1.2.6. Команда и её параметры**
- Команды можно написать с одну линию разделяя их точкой с запятой: **cmd1; cmd2; … cmdN;**
- Команда - это «**имя_команды**  _аргументы_команды_»
- **Экранирование спецсимволов** можно с помощью обратной косой черты **«\»** или **кавычками** (пробел - «\ »)
- **Двойные кавычки** в отличии от косой черты _не лишают смысла некоторым символам_ (типа **!**, **`**, **$**, **экранирование** (\))

**1.2.7. Шаблоны имён файлов**
- Чтобы произвести операцию на несколько файлов можно воспользоваться **regex**-ом (шаблон, типа *, ?, ^ и т.д.)
- **rm *~** - удалить все файлы в текущей директории, в имена файлов которых в конце стоит знак тильда «~» 

**1.2.8. История команд и автодописывание (autocompletion) имён файлов**
- Чтобы не набирать имя команда или файла с начала до конца можно нажать Tab и система допишет оставшиеся символы если найдёт эту строку в сохранённой истории
- Историю можно посмотреть командой **history** (покажет номер команды и команду)
- Командой «**!**_номер_команды_в_истории_» можно выполнить ту команду (**!!** - последнюю введенную команду)
- Сочетанием **Ctrl+R** и написанием строки можно **искать** _эту строку_ в _истории_

**1.2.9. Управление выполнением задач**
- **«Ситуация конца файла»** - _поток данных_ (поток ввода) в системе может быть считан **с клавиатуры** или **с файла**. При считывании с файла конец файла соответствует последней просчитанной строке, а в случае с клавиатурой это будет сочетание клавиш **Ctrl+D**
- Для завершения сеанса с открытым терминалом лучше использовать вышесказанное сочетание (**Ctrl+D**) - это будет корректное действие, а закрыть окно терминала средствами оконного менеджере (нажать на икс) - некорректно, так как _выполняющиеся программы этого терминала никуда не исчезнут_
- **Ctrl+C** - принудительное завершение текущей команды
- Нельзя использовать сочетание **Ctrl+Z** (временно приостанавливает выполнение команды, а не завершает его)
- **Ctrl+S** - позволяет сделать паузу вывода в терминал
- **Ctrl+Q** - позволяет отключить паузу вывода в терминал
- Прежде чем завершить зависшую программу лучше сначала проверить не поставлена ли команда на паузу
- Если _Ctrl+С, Ctrl+\, Ctrl+Q_ не помогли _завершить команду_, то необходимо **принудительно завершить процесс**
- **Процесс** - программа, которая запущена и в настоящее время выполняется в системе
- Все процессы в системе _имеют свои_ **уникальные номера**, чтобы _управлять ими_
- _Список процессов выполняющихся_ в данном конкретном сеансе можно узнать с помощью команды **ps** (processes)
- **ps ax** (_axu_) - покажет детали. Можно также использовать **top** (**q** чтобы выйти из top)
- Процесс можно **снять (убить)** с помощью _сигнала_ (тоже самое происходит при _Ctrl+С, Ctrl+\_)
- _Отправить процессу произвольный сигнал_ может команда **kill** (**kill SIGNAL PROCESS_ID** - _kill -9 123_ (or _kill KILL 123_))
- В двух случаях kill не сможет снять процесс: 
1) Процесс предок (который запустил данный процесс) не требует от системы инфо про свой дочерний процесс, данный процесс становится зомби-процессом. Не занимает ресурсов, только хранится в таблице процессов 
2) Процесс мог выполнить системный вызов, в ходе которой система перевела процесс в режим сна. Обычно это длится не более секунды, но если оно заняло больше, то это значит что ваш диск (физически) неисправен. Тут ничто вам не поможет. Процесс зомби отмечается буквой Z в поле STAT и состоянием defunct (В состояние сна можно перевести процесс следующим образом, воткнуть флешку и перевести туда большой файл, во время загрузки вытащить сразу флешку, это плохая идея, но не хуже сломанного диска)

**1.2.10 Выполнение в фоновом режиме**
- Чтобы запустить команду в фоновом режиме и не ждать его завершения необходимо **в конце команды добавить знак &** 
Пример: **_updatedb_ &**  - в фоновом режиме обновляются данные путей (для locate)
- Для _проверки состояния_ команды можно использовать команду **jobs** (выводит список команд запущенных в фоновом режиме)
- Статусы бывают Done, Terminated, Running, Exit 1
- _Для отправки сигнала_ процессам запущенным в фоновом режиме: **kill %_BG_PROCESS_NUMBER_** (_kill %2_)
- Чтобы не ждать запущенную обычную команду и запустить его в фоновом режиме надо  
1) нажать **Ctrl+Z** - приостановить процесс 
2) затем написать **bg**
- **Ctrl+Z** - временно приостанавливает выполнение команды, а не завершает его

**1.2.11 Перенаправление потоков ввода-вывода**
