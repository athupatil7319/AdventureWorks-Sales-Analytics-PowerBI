# DAX Measures

## Total Sales

```DAX
Total Sales =
SUM(Fact_Sales3[SalesAmount])

Total Profit =
SUM(Fact_Sales3[Profit])

Profit Margin % =
DIVIDE(
    [Total Profit],
    [Total Sales],
    0
)

Average Order Value =
DIVIDE(
    [Total Sales],
    [Total Orders],
    0
)
