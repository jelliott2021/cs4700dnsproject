John Elliott 002181673

High level approach
While coding this project my high level approach was to first to parse the example.com.zone file to a map that I can use for requests. After this I worked on accepting A then CNAME and then MX requests.

Challenges
The biggest challenge I faced was the parsing the example.com.zone file to a map and then understanding the formatting needed for the python dnslib and how to add answers along with using the map of the zone

Overview of testing
I tested this code by mainly using the debugging feature on vscode for python in addition to using print for the console to see the correct urls are being visited. Along with using run file and configs to test what features were working and which were failing