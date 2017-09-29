# python-whois
<i>Whois</i> query with <strong><i>Python</i></strong>

<h1>Usage</h1>

```
usage: whois.py [-h] [-domain DOMAIN] [--allofthem] [-save SAVE]

optional arguments:
  -h, --help      show this help message and exit
  -domain DOMAIN  Whois query.
  --allofthem     Whois query.
  -save SAVE      Saves Queries.
```

<h1>Examples</h1>
<h2>Basic query</h2>

```
whois.py -domain example.com
```

<h2>More queries</h2>

```
whois.py -domain example.com;net;biz;org
```

<h2>Query declared all domains.(Not declared all domains in internet)</h2>

```
whois.py -domain example.com --allofthem
```
<h2>Save queries</h2>

```
whois.py -domain example.com -save C:/example.txt
```
```
whois.py -domain example.com -save example.txt
```
<h1>Using as library</h1>

```python
import whois
result_query = whois.whois_query("www.google.com")#Returns query result to result_query.
```


