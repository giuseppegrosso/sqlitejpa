# SqliteJpa

SqliteJpa is a spring boot project that implements Hibernate 5 Dialect for sqlite

- Spring boot v. 2.4.3
- spring jpa
- support sqlite dialect

## How do I Download and Create the Sqlite Database?

Download the repository, compile and launch in intellij or eclipse or visualstudio code.
After installation run the command

```
mvn clean install
java -jar .\target\jpaSqlite-0.0.1-SNAPSHOT.jar --server.port=8080 --spring.profiles.active=sqlite
```

## SQLite Compliant

- Tested with SQLite 3.25.2

## Development

### System Requirements

- Intellij comunity edition
- Eclipse
- Visual Studio Code
- Sqlite v 3.25.2

## License

[MIT](https://choosealicense.com/licenses/mit/)
