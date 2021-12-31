# python3语法快查

--

```python
# 日期和字符串互转 https://docs.python.org/zh-cn/3/library/datetime.html#strftime-strptime-behavior
import datetime

dt_date = datetime.datetime.now()
print ("The Current date is:" ,dt_date)
print("In specified format:", dt_date.strftime("%A, %d %b %Y"))

cur_dt1 = datetime.datetime.today()
dt_str1 = '{:%a, %b %d %Y}'.format(cur_dt1)
dt_str2 = '{:%A, %B %d %Y}'.format(cur_dt1)
dt_str3 = '{:%m/%d/%Y}'.format(cur_dt1)
dt_str4 = '{:%d-%m-%Y}'.format(cur_dt1)
dt_str5 = '{:%m/%d/%y %H:%M %S}'.format(cur_dt1)
dt_str6 = '{:%m/%d/%y %I:%M %S %p}'.format(cur_dt1)
```
