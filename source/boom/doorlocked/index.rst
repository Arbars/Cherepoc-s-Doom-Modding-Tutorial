Типы закрытых (на ключ) дверей.
===============================

Эти двери отличаются от предыдущих тем, что для того, чтоб их открыть, нужно заиметь ключ(и). Запас фичей таких дверей более маленький. Опция # Of Keys: в некоторых редакторах допущена ошибка - когда ставите параметр 3, он будет действовать как 6, а когда ставите 6, то будет действовать как 3.

Типы закрытых (на ключ) дверей.
-------------------------------

.. table:: 

    +------------------------+-----------------------+--------------------+----------------------------------------+
    | Название опции         |    Описание опции     | Название аргумента |              Описание аргумента        |
    +========================+=======================+====================+========================================+
    |                        |                       |         Slow       | Медленная - как пол или потолок        |
    |                        |                       +--------------------+----------------------------------------+
    |          Speed         |    Скорость двери     |        Normal      | Обычная - как обычная дверь            |
    |                        |                       +--------------------+----------------------------------------+
    |                        |                       |         Fast       | Быстрая - как быстрая дверь            |
    |                        |                       +--------------------+----------------------------------------+
    |                        |                       |        Turbo       | Турбо - в 2 раза быстрее быстрой двери |
    +------------------------+-----------------------+--------------------+----------------------------------------+
    |                        |                       |         o->c       | Открыть - закрыть                      |
    |                        |     Действие          +--------------------+----------------------------------------+
    |           Kind         |                       |          о         | Открыть и не закрывать                 |
    +------------------------+-----------------------+--------------------+----------------------------------------+
    |                        |                       |         Any        | Любой.                                 |
    |                        |                       +--------------------+----------------------------------------+
    |                        |                       |         rc         | Красный ключ - карта.                  |
    |                        |                       +--------------------+----------------------------------------+
    |                        |                       |         bc         | Синий ключ - карта.                    |
    |                        |                       +--------------------+----------------------------------------+
    |                        |                       |         yc         | Жёлтый ключ - карта.                   |
    |          Lock          | Какой ключ открывает  +--------------------+----------------------------------------+
    |                        |                       |         rs         | Красный череп.                         |
    |                        |                       +--------------------+----------------------------------------+
    |                        |                       |         bs         | Синий череп.                           |
    |                        |                       +--------------------+----------------------------------------+
    |                        |                       |         ys         | Жёлтый череп.                          |
    |                        |                       +--------------------+----------------------------------------+
    |                        |                       |         all        | Все (зависит от опции #ofkeys).        |
    +------------------------+-----------------------+--------------------+----------------------------------------+
    |                        | Сколько нужно ключей, |          3         | 3 любых ключа (возможно 6).            |
    |        # Of Keys       | если аргумент опции   +--------------------+----------------------------------------+
    |                        | lock = all?           |          6         | 6 ключей (возможно 3 любых).           |   
    +------------------------+-----------------------+--------------------+----------------------------------------+
    
