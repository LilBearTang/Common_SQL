```sql
  --将Datetime转换为Data再比较，where条件：
  convert(date,a.交易记账日期) >= convert(date,b.开始日期)

  --将它们按你要求的格式转换为字符串后再比较，where条件：
  convert(varchar,a.交易记账日期,102) >= convert(varchar,b.开始日期,102)
```




