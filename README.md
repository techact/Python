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
