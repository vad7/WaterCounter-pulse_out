# Water-Counter-pulse-out-
Дополнительная плата, устанавливаемая на обычный водо-счетчик. Большое количество импульсов на литр. Протестирована на водосчетчике Zenner ETK-N-MZ. 

В схеме применяется оптодатчик, который смотрит на "шестеренку" водосчетчика и таким образом снимает снимает показания.<br>
Максимальная нагрузка на импульсный выход - 20 mA.<br>
Можно установить делитель (ячейка #00 в EEPROM).<br>
Автонастройка порогов - перед включением замкнуть KEY более чем на 3 секунды и отпустить, светодиод мигнет быстро 5 раз. В течении 60 секунд нужно пропускать воду через счетчик, после этого пороги будут презаписаны.<br>
Если замкнуть KEY, то в шестнадцатеричном виде будет промиган светодиодом накопленный счетчик (между цифрами 2 быстрых мигания).<br>

