# Trabajo-Consulta-2-Conexi-n-base-de-datos-relacional
Consulta

1. ¿Qué es JDBC y cuáles son sus componentes?

     JDBC (Java Database Connectivity) es una API estándar de Java que permite a las aplicaciones Java interactuar con bases de datos relacionales. JDBC actúa como un puente entre la 
     aplicación y la base de datos, facilitando la ejecución de operaciones como consultas, actualizaciones y transacciones.

     Componentes de JDBC: 
   
         * Driver JDBC: Es un controlador que actúa como interfaz entre la aplicación Java y la base de datos. Ejemplos: MySQL JDBC Driver, PostgreSQL JDBC Driver.
         * Connection: Representa una conexión activa con una base de datos.
         * Statement: Permite ejecutar consultas SQL estáticas.
         * PreparedStatement: Similar a Statement, pero con soporte para consultas parametrizadas.
         * CallableStatement: Usado para ejecutar procedimientos almacenados.
         * ResultSet: Contiene los datos obtenidos de una consulta SQL.
         * SQLException: Maneja excepciones relacionadas con la base de datos.

2. Documente 2 librerías de Scala que permitan conectarse a una base de datos relacional. En una tabla resuma sus diferencias.

      Dos librerías populares en Scala son Slick y Doobie.


  # Comparación entre Slick y Doobie

| **Característica**       | **Slick**                                     | **Doobie**                                     |
|---------------------------|-----------------------------------------------|-----------------------------------------------|
| **Paradigma**             | ORM (Object-Relational Mapping)              | Interfaz funcional pura para JDBC             |
| **Nivel de abstracción**  | Alto (trabaja con clases mapeadas a tablas)  | Medio (operaciones SQL directas)              |
| **Compatibilidad**        | Altamente integrado con Scala                | Compatible con Cats Effect y otras librerías FP |
| **Aprendizaje**           | Fácil para usuarios de ORM                   | Más técnico, requiere conocimientos de FP     |
| **Ejecución**             | Lazy (ejecución diferida de operaciones)     | Eager (ejecución inmediata de consultas)      |


   
3. Documentar cómo establecer una conexión a una base de datos relacional (mysql). Siga los siguientes pasos:
     * Genere una base de datos en mysql
     * Genere una tabla con datos de prueba
     * Desde Scala establezca la conexión a la base datos
     * (opcional) Desde Scala realice la consulta de todos los datos de la tabla de prueba.

El tercer punto lo documenta adjuntando capturas de pantalla. Adjuntar referencias.




