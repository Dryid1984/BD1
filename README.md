# BD1

Кейс
1.1
Реляционные SQL базы данных. Они строго структурированы и связаны друг с другом. PostgreSQL или MySQL они обеспечивают ACID-совместимость, поддерживают сложные SQL-запросы. 
1.1*
Хеширование занимает длительно время, используем алгоритм хеширования или библиотеки, которые могут помочь ускорить процесс хеширования например: OpenSSL, MurmurHash2
1.2
Для лендингов: NoSQL базы данных часто используют для работы с большим объемом данных, что полезно при хранении данных с различных лендингов. MongoDB, обеспечивает хорошую производительность при обработке больших объемов данных. NoSQL базы данных также могут быть полезны и для CRM. Они обеспечивают быструю запись и чтение данных, а так же позволяет адаптироваться к изменениям в структуре данных. 
Например Apache Cassandra
1.2* да, Apache Cassandra. Apache Cassandraбеспечивает возможность создания различных таблиц для различных типов данных, что позволяет эффективно хранить и обрабатывать данные из разных источников
1.3
PostgreSQL обеспечивает ACID-совместимость, определения структуры данныхю
1.3*
PostgreSQL создание отдельной схемы существующей базы данных
1.4
Neo4j. Графовые базы данных специально разработаны для работы с данными, имеющими сложные связи, что делает их эффективным инструментом для решения задач, связанных с маршрутизацией и распределением ресурсов.
1.4* да
2	Транзакция
1	Проверка доступности средств на счете пользователя.
2	Заблокировать средства на счете пользователя
3	Выполнить операцию.
4	Зафиксировать изменения в базе данных.
5   Разблокировать средства на счете пользователя после успешной транзакции.
6	Отправить подтверждение об успешном завершении транзакции пользователю.
3 SQL vs NoSQL
1.	ACID-совместимость: SQL-системы обеспечивают ACID-транзакции, что обеспечивает надежность и целостность данных в приложениях, где это критически важно.
2.	Хорошо структурированные запросы. Базы данных SQL используют структурированный язык запросов, что делает их идеальными для сложных задач обработки данных.
3.	Стандартизация и инструменты: SQL является широко используемым языком запросов, и для него существует множество инструментов и библиотек для работы с данными, что облегчает разработку и поддержку приложений.
4.	Поддержка сложных отношений между данными: SQL-системы предоставляют механизмы для работы с сложными отношениями между данными, что может быть полезно в некоторых типах приложений.
5.	Транзакционная безопасность: SQL-системы обеспечивают транзакционную безопасность, что важно для приложений, где целостность данных имеет высокий приоритет.
4 Кластеры
1.	Если данные имеют сложную структуру или требуют гибких запросов, то NoSQL базы данных могут быть предпочтительны. Если требуется поддержка транзакций и сложных SQL-запросов, то реляционные SQL базы данных могут быть более подходящим выбором.
2.	При обработке большого объема данных на 1000 машинах важно, чтобы СУБД могла эффективно масштабироваться горизонтально. NoSQL базы данных и некоторые NewSQL базы данных могут обеспечить лучшую горизонтальную масштабируемость.
3.	MapReduce эффективы для параллельной обработки больших объемов данных.
4.	При таком масштабе важно учитывать отказоустойчивость и производительность системы. NoSQL базы данных и модели распределенных вычислений обеспечивают более высокую отказоустойчивость и производительность.



