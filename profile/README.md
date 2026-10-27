FluDa(**Flu**ent **Da**ta Toolkit for Jakarta EE/CDI) is a lightweight, modular data-access suite designed specifically for standard Jakarta EE and CDI environments. It provides a developer-friendly, fluent programming model that mirrors modern data APIs without requiring full-blown Spring frameworks or introducing bulky, legacy dependencies. The toolkit is organized into six standalone, high-level core feature pillars:

* **JDBC Client** ([`jdbc-client`](https://github.com/fludakit/jdbc-client)): A lightweight, framework-agnostic fluent JDBC client that mirrors the developer experience of Spring's `JdbcClient` without requiring Spring.
* **SQL Initialization** ([`sql-init`](https://github.com/fludakit/sql-init)): Automates database schema management and data population on application startup.
* **Resource Local Transaction Support** ([`tx`](https://github.com/fludakit/tx)): Container-agnostic declarative and programmatic transaction boundaries backed directly by a standard DataSource or JPA.
* **Data** ([`data`](https://github.com/fludakit/data)): Compile-time repository generation for Jakarta Data, producing type-safe JDBC-backed implementations with optional query-by-method-name support.
* **Mail** ([`mail`](https://github.com/fludakit/mail)): A simple mail abstraction with built-in Jakarta Mail (SMTP) support and pluggable providers for third-party services like SendGrid.
* **JMS Client** ([`jms-client`](https://github.com/fludakit/jms-client)): A fluent client for Jakarta Messaging that mirrors the developer experience of Spring's `JmsClient`, with payload converters, connection caching, and CDI wiring for Java SE and Jakarta EE.

See the [reference documentation](https://fludakit.github.io/) for more details.
