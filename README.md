# Flipkart Online book shopping

## Tables

#### Table 1: Books

| Book Name | Category | Price | Rating|
|-----------|----------|-------|-------|
| One Day Run | Fiction | 2000 | 5 |
| Shoot Day | Comics | 500 | 5 |
| Last Night | Fiction | 1300 | 3 |
| About murder | Fiction | 1750 | 4 |
| Scooby-doo | Comics | 800 | 2 |

#### List All Books
select * from Books;

#### Price-Low to High
select * from Books ORDER BY Price asc;

#### Price-High to Low
select * from Books ORDER BY Price desc;

#### List books based on Category
select * from Books where Category=Comics;

#### List books order based on Rating from 3 to 5
select * from Books where Rating Between 3 and 5

#### List all books with Price range from 500 to 1500
select * from Books where Price Between 500 and 1500
