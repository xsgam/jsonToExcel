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


update for support  jsonObject in jsonObject:
[
    {
        "A": "001",
        "B": "TEST1",
        "c": [{"c1":1,"c2":2},{"c3":1,"c3":2}],
        "d": {"d1":1,"c2":2}
    },
    {
        "A": "002",
        "B": "TEST2",
        "c": [{"c1":1,"c2":2},{"c3":1,"c3":2}],
        "d": {"d1":1,"c2":2}
    }
]
