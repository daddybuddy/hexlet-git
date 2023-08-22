## Документация
### Нотации для документирования
- UML https://habr.com/ru/post/458680/
- ERD https://habr.com/ru/post/440556/
### Спецификация OpenAPI
- https://starkovden.github.io/ - (курс по документированию REST API)
- https://swagger.io/ - (много информации о документировании и проектировании API
- https://swagger.io/tools/swagger-editor/ - инструмент для спецификации API в формате OpenAPI)
## СУБД
### Нормальные формы:
https://habr.com/ru/post/254773/

https://ru.wikipedia.org/wiki/%D0%9D%D0%BE%D1%80%D0%BC%D0%B0%D0%BB%D1%8C%D0%BD%D0%B0%D1%8F_%D1%84%D0%BE%D1%80%D0%BC%D0%B0

### Индексы в таблицах - зачем нужны, какие последствия введения
### Посложнее
- https://tproger.ru/articles/indeksy-v-postgresql/
- https://postgrespro.ru/docs/postgresql/14/indexes-intro
- Уникальные индексы: https://postgrespro.ru/docs/postgresql/13/indexes-unique
- Анатомия плана запроса в PostgreSQL: https://sql-ex.ru/blogs/?/AnatomiJa_plana_zaprosa_v_PostgreSQL.html
- EXPLAIN: https://postgrespro.ru/docs/postgresql/14/sql-explain
- ANALYZE: https://postgrespro.ru/docs/postgresql/14/sql-analyze
- Проектирование индекса в базах данных и оптимизация: https://sql-ex.ru/blogs/?/Proektirovanie_indeksa_v_bazah_dannyh_i_optimizaciJa_nekotorye_rekomendacii.html
- Типы индексов PostgreSQL: https://postgrespro.ru/docs/postgresql/14/indexes-types
Псс, парень… индекс нужен? : https://habr.com/ru/company/tensor/blog/659889/
### Транзакции в БД, ACID
- https://gb.ru/posts/acid_cap_transactions
- https://youtu.be/gRUhFp8DhLM
- https://www.flenov.info/books/read/free-sql-book/116
- https://habr.com/ru/post/537594/
### Партиционирование, шардирование БД - зачем и как
- https://web-creator.ru/articles/partitioning_replication_sharding
- https://highload.today/sharding-i-replikatsiya/
- https://postgrespro.ru/docs/postgresql/14/ddl-partitioning
### Оконные функции SQL 
- https://postgrespro.ru/docs/postgresql/9.4/tutorial-window#:~:text=%D0%9E%D0%BA%D0%BE%D0%BD%D0%BD%D0%B0%D1%8F%20%D1%84%D1%83%D0%BD%D0%BA%D1%86%D0%B8%D1%8F%20%D0%B2%D1%8B%D0%BF%D0%BE%D0%BB%D0%BD%D1%8F%D0%B5%D1%82%20%D0%B2%D1%8B%D1%87%D0%B8%D1%81%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%B4%D0%BB%D1%8F,%D0%BE%D0%B4%D0%BD%D1%83%2C%20%D0%B0%20%D0%BF%D1%80%D0%BE%D0%B4%D0%BE%D0%BB%D0%B6%D0%B0%D1%8E%D1%82%20%D1%81%D1%83%D1%89%D0%B5%D1%81%D1%82%D0%B2%D0%BE%D0%B2%D0%B0%D1%82%D1%8C%20%D0%BE%D1%82%D0%B4%D0%B5%D0%BB%D1%8C%D0%BD%D0%BE