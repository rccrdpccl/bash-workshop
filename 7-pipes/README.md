1) Search in sherlock for the term "softonic" (en) and show the first
result's program Name.
In order to search in Sherlock, you need to perform a GET request with
header Accept-Language set to the desired language.

```
GET "https://sherlock.sftapi.com/search/Bobafett?query=softonic"
Accept-Language: en_US
```

Tips: curl, jq

2) Download and uncompress the file at the following url. Can you download it and unzip with only one line of code?

ftp://ita.ee.lbl.gov/traces/NASA_access_log_Jul95.gz

3) What is the most requested URL? How many hits it had in the logs?

Tips: uniq

