# IIF
If `$1`, return `$2`, else return `$3`.

## Syntax
```SQL
IIF($1, $2, $3)
```

## Parameters

### `$1`
Should evaluate to a [boolean](./other/types.md#boolean)

### `$2`
May be anything

### `$3`
May be anything


## Same as
```SQL
CASE
	WHEN $1 THEN $2
	END $3
END
```