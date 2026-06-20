# Streams

## Filter Values

```java
list.stream().filter(x -> x > 10).toList()

## Map Values

list.stream().map(x -> x * 2).toList()

## Count Elements

list.stream().count()

## Find First

list.stream().findFirst()