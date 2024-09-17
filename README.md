# Задание

```
Задание 1: Создайте класс Person с полями name и age.
Реализуйте сериализацию и десериализацию этого класса в файл.
```

## Решение.

Сделал три варианта:
1) Через интерфейс `Serializable`.
2) Через интерфейс `Externalizable`;
3) Через библиотеку `jackson`, в формат `JSON`. 

Для `jackson` добавил зависимость в `pom.xml`:
```xml
    <dependencies>
        <dependency>
            <groupId>com.fasterxml.jackson.core</groupId>
            <artifactId>jackson-databind</artifactId>
            <version>2.17.2</version>
        </dependency>
    </dependencies>
```
