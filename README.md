# jsonToExcel
A small tool , convert JSON data  to CVS

JSON like this：

[
    {
        "A": "001",
        "B": "TEST1"
    },
    {
        "A": "002",
        "B": "TEST2"
    }
]


#  3/4/2022 update for support  jsonObject in jsonObject 
Json like this:
```
[
    {
        "A": "001",
        "B": "TEST1",
        "c": [{"c1":11,"c2":12},{"c1":13,"c2":14}],
        "d": {"d1":101,"d2":102}
    },
    {
        "A": "002",
        "B": "TEST2",
        "c": [{"c1":22,"c2":23},{"c1":24,"c2":25}],
        "d": {"d1":201,"c2":202}
    }
]
```

output csv:
```
A,B,c,d1,d2
"001","TEST1",("11" "12"|"13" "14"),"101","102"
"002","TEST2",("22" "23"|"24" "25"),"201","202"
```
