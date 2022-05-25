# SQL_Assgnmt



Ans1-   select count(*) From SalesPeople Where Sname Like 'A%' OR Sname Like 'a%';
Ans2-   select count(*) From SalesPeople WHERE 2000 < (SELECT Amt FROM Orders WHERE Snum=SalesPeople.Snum;);
Ans3-   select count(*) From SalesPeople Where City='NewYork';
Ans4-   select count(*) From SalesPeople Where City='London' And City='Paris';
Ans5-   select Sname, 0Date, Count(Distinct Orders.Snum) AS TotalOrders From SalesPeople, Orders Where SalesPeople.Snum = OIrders.Snum;
