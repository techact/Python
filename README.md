## Table of Contents
- [Python](#Python)
    - [Dictionary](#Dictionary)
    - [List](#List)
    - [FormatString](#Format String)

- [Python-Boto](#Boto)
    - [EC2](#EC2)
    - [EC2](#EC2)
    - [EC2](#EC2)
    - [EC2](#EC2)
    - [EC2](#EC2)
    - [EC2](#EC2)
    - [EC2](#EC2)

## Python

### Dictionary

##### Example : 1
```
dict = {'name': 'Peter', 'Gender': 'Male', 'Age': 18}
print(dict['name']) # printing name
```
##### Output
```
Peter
```
##### Example : 2
```
d = {'dict1': {'name': 'Peter', 'Gender': 'Male', 'Age': 18}, 'dict2': {'country': 'India', 'State': 'TamilNadu'}}
print d['dict1']['Age']
print d['dict2']['country']
for k, v in d.items():
    print k, v
    if k == 'dict2':
        print d['dict2']['State']
```
##### Output
```
18
India
dict1 {'Gender': 'Male', 'Age': 18, 'name': 'Peter'}
dict2 {'country': 'India', 'State': 'TamilNadu'}
TamilNadu
```

#import datetime
from datetime import datetime
from datetime import datetime, timedelta
# get current date
now = datetime.now()

# convert current date into timestamp
timestamp = datetime.timestamp(now)

print("Date and Time :", now)
print("Timestamp:", timestamp)

now = datetime.now()
print ("Today's date: ", str(now))

#add 15 days to current date
now = datetime.now()
plus_24_hours = now + timedelta(seconds = 86400)
print('Date after 15 days: ', future_date_after_15days)
ts = datetime.timestamp(future_date_after_15days)
x = str(ts).split('.')[0]
print(x)


now = datetime.now()
plus_24_hours = now + timedelta(seconds = 86400)
ts = datetime.timestamp(plus_24_hours)
x = str(ts).split('.')[0]
print(x)



import datetime
a = datetime.datetime(100,1,1,11,34,59)
b = a + datetime.timedelta(0,3) # days, seconds, then other fields.
print(a.time())
print(b.time())



ENV TZ 'Europe/Tallinn'
    RUN echo $TZ > /etc/timezone && \
    apt-get update && apt-get install -y tzdata && \
    rm /etc/localtime && \
    ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && \
    dpkg-reconfigure -f noninteractive tzdata && \
    apt-get clean
    
