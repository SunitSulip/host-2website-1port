# host-2website-1port


Task:- hosting 2 websites in one port.

Approach:-  **as we can identify a website by ip/port/hostname. So as the ip & port are same we can host 2 websites by 2 different hostnames**

Steps-
-> create 2 websites with different hostname in iis-server
Web-1
<img src="/Screenshot/iis_server_of web_1.PNG">

Web-2
<img src="/Screenshot/iis_server_of web_2.PNG">

-> Then we have to add some mapping of those domain name for DNS *{make sure to open the host file under RUN AS ADMINISTRATOR}*
in Windows(host file)[location:- **C:\Windows\System32\drivers\etc **]
<img src="/Screenshot/host_file.PNG">

add mapping to the host-file 
<img src="/Screenshot/mapping.PNG">

-> Then the browser can access the websites-
<img src="/Screenshot/web_1.PNG">
<br>
<img src="/Screenshot/web_2.PNG">
