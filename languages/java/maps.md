# Maps

## Check Key Exists

```java
map.containsKey(key)

## Get Default Value

map.getOrDefault(key, 0)

## Iterate Map

map.forEach((k,v) -> System.out.println(k + ":" + v))

## Put If Absent

map.putIfAbsent(key, value)