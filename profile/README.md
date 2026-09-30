FluDa(**Flu**ent **Da**ta Toolkit for Jakarta EE/CDI) is a lightweight, modular data-access suite designed specifically for standard Jakarta EE and CDI environments. It provides a developer-friendly, fluent programming model that mirrors modern data APIs without requiring full-blown Spring frameworks or introducing bulky, legacy dependencies. The toolkit is organized into three standalone, high-level core feature pillars:

* **JDBC Client**([`jdbc-client`](https://github.com/fludakit/jdbc-client)): A lightweight, framework-agnostic fluent JDBC client that mirrors the developer experience of Spring's `JdbcClient` without requiring Spring.
* **Resource Local Transaction Support** ([`tx`](https://github.com/fludakit/tx)): Container-agnostic declarative and programmatic transaction boundaries backed directly by a standard DataSource or JPA. (*coming soon*)
* **SQL Initialization** ([`sql-init`](https://github.com/fludakit/sql-init)): Automates database schema management and data population on application startup. (*coming soon*)

See the [reference documentation](https://fludakit.github.io/) for more details.
