# bsi_security

Authors:

    Dmytro Yurchenko

    Daryna Kovyrina
    
Wybrana aplikacja:    
    
    https://github.com/stamparm/DSVW
    
Podsumowanie:

    Script 1:
    GET 200 OK
    POST 501 Unsupported method ('POST')
    PUT 501 Unsupported method ('PUT')
    DELETE 501 Unsupported method ('DELETE')
    OPTIONS 501 Unsupported method ('OPTIONS')
    TRACE 501 Unsupported method ('TRACE')
    TEST 501 Unsupported method ('TEST')
    Script 2:
    Server: BaseHTTP/0.6 Python/3.9.1
    Date: Tue, 26 Jan 2021 14:49:37 GMT
    Via: Not found
    X-Powered-By: Not found
    X-Country-Code: Not found
    Script 3:
    http://127.0.0.1:65412/ report:
    X-XSS-Protection not set properly, XSS may be possible: 0
    X-Content-Type-Options not set
    HSTS header not set, MITM attacks may be possible
    Content-Security-Policy missing
    Script 4:
    Login successful, password: text1234
    
Wybrane narzedzia do testowania:

    Bandit - is a comprehensive source vulnerability scanner for Python, SAST
    Nikto - DAST

###Bandit
![alt text](https://github.com/HollisLynch/bsi_security/blob/main/lab13-images/Знімок%20екрана%202021-02-08%20о%2007.41.29.png?raw=true)
![alt text](https://github.com/HollisLynch/bsi_security/blob/main/lab13-images/Знімок%20екрана%202021-02-08%20о%2007.42.03.png?raw=true)
![alt text](https://github.com/HollisLynch/bsi_security/blob/main/lab13-images/Знімок%20екрана%202021-02-08%20о%2007.42.21.png?raw=true)
![alt text](https://github.com/HollisLynch/bsi_security/blob/main/lab13-images/Знімок%20екрана%202021-02-08%20о%2007.42.38.png?raw=true)
![alt text](https://github.com/HollisLynch/bsi_security/blob/main/lab13-images/Знімок%20екрана%202021-02-08%20о%2007.42.50.png?raw=true)
![alt text](https://github.com/HollisLynch/bsi_security/blob/main/lab13-images/Знімок%20екрана%202021-02-08%20о%2007.43.21.png?raw=true)
![alt text](https://github.com/HollisLynch/bsi_security/blob/main/lab13-images/Знімок%20екрана%202021-02-08%20о%2007.43.30.png?raw=true)
![alt text](https://github.com/HollisLynch/bsi_security/blob/main/lab13-images/Знімок%20екрана%202021-02-08%20о%2007.43.51.png?raw=true)

