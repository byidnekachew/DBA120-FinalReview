## Question 1


## Question 2


## Question 3
In the SELECT clause, the column "boohbah_name" doesn't exist. Instead, the command should select the "name" column.

## Question 4
In the SELECT clause, aliases are not used, so it's ambiguous as to which column is being selected. Thus, it should be "b.boohbah_id" and "l.stand_id"

## Question 5
The WHERE clause is redundant and should thus be removed.

## Question 6
The subquery returns multiple rows, not an agregate value. Thus, you need use a multiple row function to compare each value in the WHERE clause to.

## Question 7


## Question 8
In a comparison for a WHERE clause, you can't have a multiple row function. It should be a subquery with a multiple row function instead.

## Question 9
The columns in the subquery are not in the right order and needed to be switched.

## Question 10
The wrong table is referenced in the FROM clause. It should instead be switched to be the "boohbah_stand_link" table.
