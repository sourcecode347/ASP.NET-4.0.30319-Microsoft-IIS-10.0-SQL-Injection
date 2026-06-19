# ASP.NET-4.0.30319-Microsoft-IIS-10.0-SQL-Injection
SQL Injection Exploit on ASP.NET 4.030319 With Full Database Access

<img src="https://github.com/sourcecode347/ASP.NET-4.0.30319-Microsoft-IIS-10.0-SQL-Injection/tree/main/exploiτ_poc.png" style="width:100%;height:auto;"/>

At first, a request is sent to the TARGET_URL with a list of PAYLOADS and we check for a list of Error Signatures and if any of the Error Signatures are printed 
Then it is most likely vulnerable to multiple SQLi vulnerabilities (boolean-based blind, error-based, stacked queries, time-based blind & UNION query).

These types of Payloads give us full access to the database.

It affects Windows operating systems (2016, 2022, 11, 2019 & 10).

# Exploit Title: ASP.NET 4.0.30319 + Microsoft IIS 10.0 SQL Injection
# Google Dork: N/A
# Date: 19/06/26
# Exploit Author: SourceCode347
# Vendor Homepage: https://microsoft.com
# Software Link: https://dotnet.microsoft.com/en-us/apps/aspnet
# Version: ASP.NET 4.0.30319
# Tested on: Windows 2016,2022,11,2019,10
# CVE : 
