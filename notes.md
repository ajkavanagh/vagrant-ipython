# Notes


# Code Samples

```python
statement = (select([func.count('*')])
             .select_from(table)
             .where(
                and_(table.c.field1 > some_value,
                    or_(table.c.field2 != None,
                        table.c.field3 < something_else))))
```
