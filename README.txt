SistemaHotelWeb - instruções

1) Crie o banco MySQL 'sistemahotel' (veja script in project/sql/create_database.sql)
2) Ajuste usuário/senha em br.com.sistemahotel.util.ConnectionFactory if necessary.
3) Import project into NetBeans: File -> New Project -> Java Web -> Web Application and point to this folder, or create project and copy src/web.
4) Add MySQL JDBC driver to project libraries (mysql-connector-java) and run on Tomcat.
