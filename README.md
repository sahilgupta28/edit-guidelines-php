# Laravel
## Migrations
- The down() function is required.
- The down() function of migration must have code reverse to up() function.
## first() vs get()
- Use first() where we need only one record.
- Use get() where we need to get more than one records.
- The first() will not return array of records. So we can avoid the use of index 0 by using first().
