[![Java CI with Gradle](https://github.com/Denis-Zhigun/aqa-2.4/actions/workflows/gradle.yml/badge.svg)](https://github.com/Denis-Zhigun/aqa-2.4/actions/workflows/gradle.yml)

### Задача
Ключевой кейс: При успешном переводе, возвращение назад на страницу со списком карт.

Требования к доменным методам, реализованным через Page Objects:

1. Перевода с определённой карты на другую карту n'ой суммы
2. Проверки баланса по карте (со страницы списка карт).
Тестируемая функциональность: отправка формы.

### Решение
1. Созданы необходимые доменные методы.
2. Проведено тестирование функциональности перевода между картами одного аккаунта.
3. Выявлены следующие ошибки {https://github.com/Denis-Zhigun/aqa-2.4/issues/1#issue-895784054}

### Баги
1. Возможность перевода суммы больше доступной по имеющемуся остатку по карте {https://github.com/Denis-Zhigun/aqa-2.4/issues/1#issue-895784054}
