# jsonToExcel
A small tool , convert JSON data  to CVS

JSON like this：
```
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
```

update for support  jsonObject in jsonObject:
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
