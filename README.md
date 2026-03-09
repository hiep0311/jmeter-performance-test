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



| Scenario | Avg Response Time | Throughput | Error Rate |

|--------|----------------|------------|-----------|

| Basic | 200 ms | 15/sec | 0% |

| Heavy | 350 ms | 40/sec | 0% |

| Custom | 300 ms | 25/sec | 0% |



---



\# Test Result Screenshot



!\[Summary Report](summary-report.png)



---



\# Conclusion



The website handled the simulated load without errors.  

Average response time remained stable during testing.  

The system is capable of handling moderate traffic efficiently.

