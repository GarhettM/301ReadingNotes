Select query for a specific columns
`SELECT column, another_column, …`
`FROM mytable;`

Select query for all columns
`SELECT * `
`FROM mytable;`

Select query with constraints
`SELECT column, another_column, …`
`FROM mytable`
`WHERE condition`
    `AND/OR another_condition`
    `AND/OR …;`

`!= or <>`	Case sensitive exact string inequality comparison	`col_name != "abcd"`

`%`	Used anywhere in a string to match a sequence of zero or more characters (only with LIKE or NOT LIKE)

Insert statement with values for all columns
`INSERT INTO mytable`
`VALUES (value_or_expr, another_value_or_expr, …),`
       `(value_or_expr_2, another_value_or_expr_2, …),`
       `…;`

Insert statement with specific columns
`INSERT INTO mytable`
`(column, another_column, …)`
`VALUES (value_or_expr, another_value_or_expr, …),`
      `(value_or_expr_2, another_value_or_expr_2, …),`
      `…;`

Update statement with values
`UPDATE mytable`
`SET column = value_or_expr, `
    `other_column = another_value_or_expr, `
    `…`
`WHERE condition;`

Delete statement with condition
`DELETE FROM mytable`
`WHERE condition;`