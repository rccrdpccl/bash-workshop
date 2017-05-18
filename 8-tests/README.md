1) Write a bash script that accepts a softonic instance, and it
outputs its language
```
es: es_ES
en: en_US
it: it_IT
br: pt_PT
jp: ja_JP
nl: nl_NL
pl: pl_PL
de: de_DE
fr: fr_FR
```

Example:
```
$ ./get_language es
es_ES
```

2) Validate input for the program.

3) Write a bash script that accept as a parameter a Softonic instance
and a query and based on the number of results of Sherlock's bobafett,
it will return:
"Low" < 10
"Medium" >= 10 and <= 100
"High" > 100

Url: https://sherlock.sftapi.com/search/Bobafett
Example:
```
$ ./search es mipito
Medium
```
