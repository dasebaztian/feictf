---
description: CC2024
---

# Endpoint

Preguntas Endpoint CC2024

{% file src="../.gitbook/assets/access.log" %}
Archivo para resolución del reto
{% endfile %}

De acuerdo al archivo access.log se tienen que responder las siguientes preguntas, el archivo es un extracto de registros de un servidor web. Para hacer la resolución de este reto se necesitan conocimientos del protocolo HTTP.

1.  Most frequent - Which domain is most frequently accessed?

    example.com
2.  HTTP Method - What was the most frequently used HTTP method to access the web server on that particular day?

    GET
3. Important question - Based on the access log, can you determine if there was a security incident?Yes
4.  IP Address - What is the IP address being used by the adversaries or threat actor?

    192.168.100.4
5.  MITRE - Based on the access log, what type of technique is being used by the adversaries, as per https://attack.mitre.org/?

    T1087
6.  First step - According to the logs, could you specify the exact time at which the first attack commenced? (format HH:MM:SS)

    10:38:39
7.  User agent - Using the user agent from the access log, please go to https://gchq.github.io/CyberChef/#recipe=Parse\_User\_Agent() and determine the web browser being used by the threat actor.

    Firefox
8.  Operative System . Using the CyberChef tool mentioned earlier, please determine the name of the operating system being used by the threat actor. (Please provide the name only, without the version)

    Windows
9.  Username - Based on the access log, What username that the threat actor is attempting to log in with?

    admin
10. Clock In - Based on the logs, at what exact time (in the format DD/MM/YYYY:HH:MM:SS) was the threat actor able to gain access to a user account in the system? Expected Flag Format: DD/MM/YYYY:HH:MM:SS (only numerical)

    31/07/2023:10:43:40
11. The password - What is the user admin password

    password
