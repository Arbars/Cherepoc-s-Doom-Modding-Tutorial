Свойства секторов.
==================

Яркость (Light) - может быть от 0 (всё чёрное и нифига не видно) до 255 (самое яркое).

Типы секторов.
--------------

.. list-table:: 
   :widths: 15 10 30
   :header-rows: 1
   
   * - Название
     - Номер
     - Описание
   * - Light Blinks Randomly
     - 1
     - Случайно меняется яркость сектора.
   * - Light Blinks Every 0.25 seconds
     - 13
     - Яркость сектора меняется каждые 0.25 секунды.
   * - Light Blinks Every 0.5 seconds
     - 2
     - Яркость сектора меняется каждые 0.5 секунды.
   * - Light Blinks Every second
     - 3
     - Яркость сектора меняется каждую секунду.
   * - Light Pulsate Cycle 1+ second
     - 8
     - Яркость сектора плавно переходит от 0 до того, что вы поставили и обратно.
   * - Light Pulsate every 1 second
     - 12
     - По моему, то-же самое, что и Light Blinks Every second.
   * - Light Pulsate/Flicker 2
     - 17
     - Похож на Light Blinks Randomly, но свет изменяется не так сильно.
   * - -2\5% Health Acid Floor
     - 7
     - Если стоишь на полу в этом секторе, то каждую секунду отнимается от 2 до 5 % здоровья (зависит от брони).
   * - -5\10% Health Acid Floor
     - 5
     - То-же, что и -2\5% Health Acid Floor, только отнимает от 5 до 10.
   * - -10\20% Health Acid Floor
     - 16
     - То-же, что и -2\5% Health Acid Floor, только отнимает от 10 до 20.
   * - -10\20% Health, Light Strobe every 0.5 second
     - 4
     - То-же, что и -10\20% Health Acid Floor, только каждые пол секунды изменяется уровень света.
   * - -10\20% Health, End Level When Health <=10%	
     - 11
     - То-же, что и -10\20% Health Acid Floor, только когда у игрока <=10% здоровья, уровень заканчивается (как на e1m8 после попадания в телепорт).
   * - Secret
     - 9
     - +1 секрет игроку, попавшему в этот сектор.
   * - LikeADoor Close 30 seconds After Level Start	
     - 10
     - Как дверь, закроется через 30 секунд после начала игры.
   * - LikeADoor Close 5 minutes After Level Start
     - 14
     - Как дверь, закроется через 5 минут после начала игры.
