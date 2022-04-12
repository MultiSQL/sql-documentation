# NULLIF
If `$1` equals `$2`, return `NULL`, else return `$1`.

## Syntax
```SQL
NULLIF($1, $2)
```

## Parameters

### `$1`
May be anything

### `$2`
May be anything


## Same as
```SQL
IIF($1 = $2, NULL, $1)
```