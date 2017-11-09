[![Build Status](https://travis-ci.org/java-park-mail-ru/samples.svg?branch=master)](https://travis-ci.org/java-park-mail-ru/samples)

Это репозиторий с примерами кода к лекциям. Каждый пример в нём независим от остальных и то, что они объединены в один большой и многомодульный можно игнорировать. Если вы скопируете папку с любым примером себе в отдельное место - он тоже будет работать. К некоторым лекциям дано несколько примеров - каждый из них тоже независим от всех других.

Краткий обзор файлов и примеров:
- .gitignore - лучше взять это, чем пару страниц мусора из случайного поиска в интернета
- .mvn mvnw mvnw.bat - скрипт для запуска Maven, избавляющий от необходимости ставить его в систему. Можно копировать и пользоваться, а все команды заменять с mvn something на ./mvnw something
- travis.yml - конфигурация для Travis. Можно использовать, как основу для своей конфигурации к РК2 (лекция 2-1 и 2-2).
- pom.xml, sample-2-2/pom.xml и другие с `<packaging>pom</packaging>` - конфиги мавена для сборки и проверки независимых примеров за один раз. Можно спокойно игнорировать.

Некоторые примеры требуют внешних зависимостей (СУБД) - как они настраиваются можно посмотреть в .travis.yml
Некоторые примеры имеют свои краткие README:
- [Пример 2-1](sample-2-1/README.md)
- [Пример 2-2](sample-2-2/README.md)
- [Внепрограммный пример про JMH](sample-extras/sample-jmh/README.md)
- [Внепрограммный пример про Testcontainers](sample-extras/sample-testcontainers/README.md)

Если вы нашли ошибку в любом примере, или считаете что его можно улучшить - открывайте PR или issue.



