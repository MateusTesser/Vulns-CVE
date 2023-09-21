# CVEs to be disclosure.

## FUXA <= 1.1.12 Vulns

https://github.com/MateusTesser/CVE-2023-31716 
-> The endpoint to show logs on the system "/api/logs?file=fuxa.log" have an LFI exploitation (LFI)


https://github.com/MateusTesser/CVE-2023-31717
-> It is possible to do SQL Injection into the HTTP POST id parameter passed in the body as json, being able to extract confidential information from the SQLite database (SQLi)


https://github.com/MateusTesser/CVE-2023-31718
-> Its possible to include local files into the endpoint /api/download. This endpoint is to download reports from the FUXA and can read local files from HTTP GET "name" parameter, (LFi)


https://github.com/MateusTesser/CVE-2023-31719
-> Its possible do inject SQL code into the JSON parameter "username" from the endpoint /api/signin via HTTP POST request (SQLi)
