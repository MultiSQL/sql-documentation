# IFNULL
If `$1` is `NULL`, return `$2`, else return `$1`.

## Syntax
```SQL
IFNULL($1, $2)
```

## Parameters

### `$1`
May be anything

### `$2`
May be anything


## Same as
```SQL
IIF($1 IS NULL, $2, $1)
```