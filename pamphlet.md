## 6-05 - Cash Account, part 2 Using CTE

We're gonna write queries for all the transactions that affect the cash account.

revenue is an inflow of money into the cash account. So we use sum() instead of -sum().

## 7-06 - Cash Account, part 3 Union
### Union vs join
In union, the rows are increased not the columns. But in join, the columns are increased(we add new details to the data
that already exist), but there's also a special join called cross join that increases the number of rows as well.

Note: union doesn't increase the number of cols.  

In join we add new columns

## 8-07 - Cash Account, part 4 Window function and materialized view