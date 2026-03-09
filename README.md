\# JMeter Performance Test



\## Website tested

https://www.wikipedia.org



\## Tool

Apache JMeter



---



\# Test Scenarios



\## Thread Group 1 – Basic Test

Users: 10  

Loop: 5  



Request:

GET /



---



\## Thread Group 2 – Heavy Load

Users: 50  

Ramp-up: 30 seconds  



Requests:

GET /

GET /wiki/Main\_Page



---



\## Thread Group 3 – Custom Test

Users: 20  

Duration: 60 seconds  



Requests:

GET /wiki/Computer

GET /wiki/Internet



---



\# Results



\## Summary Report



!\[Summary Report](summary-report.png)

