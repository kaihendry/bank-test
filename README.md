# bank-test
Test project for regression and load testing of bank application.
Performs calls to bank apis, verifies responses and collect statistics.
Bank application versions can be found here: https://github.com/nikitsenka/bank-go, https://github.com/nikitsenka/bank-java
#RUN
```
  jmeter -JHOST=<host> -JPORT=<port> -JNUM_USERS=1 -n -t bank-test.jmx -l results.csv
```

