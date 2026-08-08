# DAX Measures

```DAX

## Total Sales
Total Sales =
SUM(Fact_Sales3[SalesAmount])

## Total Profit

Total Profit =
SUM(Fact_Sales3[Profit])

##Profit margin
Profit Margin % =
DIVIDE(
    [Total Profit],
    [Total Sales],
    0
)

##Avreage
Average Order Value =
DIVIDE(
    [Total Sales],
    [Total Orders],
    0
)
