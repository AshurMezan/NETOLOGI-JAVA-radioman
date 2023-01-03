# Домашнее задание к занятию «Объектно-ориентированное программирование и проектирование»

Требования к работе с радиостанциями:

Номер текущей радиостанции может принимать значения только в пределах от 0 до 9.
Если текущая радиостанция — 9 и клиент нажал на кнопку next (=вызвал одноимённый метод next, с англ. — следующая) на пульте, то текущей должна стать нулевая. В остальных случаях при нажатии на эту же кнопку радио переключается просто на следующую станцию.
Если текущая радиостанция — 0 и клиент нажал на кнопку prev (=вызвал одноимённый метод prev, с англ. — предыдущая) на пульте, то текущей должна стать девятая. В остальных случаях радио переключается просто на предыдущую станцию.
Клиент должен иметь возможность выставлять номер радиостанции через прямое указание её номера. Для этого подойдёт один метод-сеттер с проверкой на допустимость номера станции.
Требования к работе с уровнем громкости звука:

Клиент должен иметь возможность увеличивать и уменьшать уровень громкости звука в пределах от 0 до 10.
Если уровень громкости звука достиг максимального значения, то дальнейшее нажатие на + (=вызов метода увеличения громкости на один, придумайте название сами) не должно ни к чему приводить.
Если уровень громкости звука достиг минимального значения, то дальнейшее нажатие на - (=вызов метода уменьшения громкости на один, придумайте название сами) не должно ни к чему приводить.

К созданному классу Radio напишите тесты, добейтесь покрытия на 100% по бранчам, обрушать сборку по покрытию при этом не нужно. Для хорошего тестирования рекомендуем вам провести тест-дизайн перед написанием тестов, так вы с большей вероятностью найдёте дефекты в вашем коде.
