# ODOOMAIN

Forget about boring attempts to type a domain that will suit the actual task.

Use a simple CLI application that does everything for you. It is enough just to schematically write a logical chain:

```sh
odoomain "(? and ?) or (? or ? or ?)"
```

Result:
```sh
['|', '&', ('EXPRESSION',), ('EXPRESSION',), '|', ('EXPRESSION',), ('EXPRESSION',), '|', ('EXPRESSION',)]
Code above was copied to clipboard!
```