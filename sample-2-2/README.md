- **JDBC** - набор интерфейсов  для доступа к СУБД из Java. Эти интерфейсы реализуют драйвера для подключения к конкретным СУБД.
- **DataSource** - один из интерфейсов JDBC, источник connection-ов к СУБД. connection-ы из этого источника после "закрытия" могут физически не закрываться, а возвращаться в источник для переиспользования (pool)
- **JdbcTemplate и NamedParametrJdbcTemplate** - обертки над jdbc, облегчающие закрытие connection-ов, итерацию по ResultSet-ам, использование транзакций из Spring
- **ORM** - прослойка между таблицами в реляционных БД и классами в ООП
- **JPA** - набор интерфейсов и аннотаций для работы с БД по принципу ORM
- **EntityManager** - JPA-интерфейс аналог Connection из JDBC
- **Hibernate** - imlements JPA
- **Spring Data JPA** - обёртка над JPA, которая добавляет еще больше магии и генерации кода в runtime

