# Laravel
## Migrations
- The down() function is required in all migrations.
- The down() function of migration must have code reverse to up() function.
- For droping multiple columns use array of columns in dropColumn() instead of mutiple dropColumn() function. 
Eq:`$table->dropColumn(['col_1', 'col_2', col_n]);`
## first() vs get()
- Use first() where we need only one record.
- Use get() where we need to get more than one record.
- The first() will not return an array of records. So we can avoid the use of index 0 by using first().
