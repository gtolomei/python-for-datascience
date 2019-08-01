About this Dataset

This data set contains 1781 unique anonymised URLs, along with a set of 18 features and a binary class label (TYPE), which indicates whether the corresponding URL is malicious (1) or not (0).

Below is a detailed description of this dataset.

- URL: it is the anonimous identification of the URL analyzed in the study.
- URL_LENGTH: it is the number of characters in the URL.
- NUMBER_SPECIAL_CHARACTERS: it is number of special characters identified in the URL, such as, "/", "%", "#", "&", ". ", "=".
- CHARSET: it is a categorical value and its meaning is the character encoding standard (also called character set).
- SERVER: it is a categorical value and its meaning is the operative system of the server got from the packet response.
- CONTENT_LENGTH: it represents the content size (in bytes) of the HTTP header.
- WHOIS_COUNTRY: it is a categorical variable, its values are the countries we got from the server response (specifically, our script used the API of Whois).
- WHOIS_STATEPRO: it is a categorical variable, its values are the states we got from the server response (specifically, our script used the API of Whois).
- WHOIS_REGDATE: Whois provides the server registration date, so this variable has date values with format DD/MM/YYY HH:MM
- WHOIS_UPDATED_DATE: through the Whois we got the last update date from the server analyzed.
- TCP_CONVERSATION_EXCHANGE: this variable is the number of TCP packets exchanged between the server and our honeypot client.
- DIST_REMOTE_TCP_PORT: it is the number of the ports detected and different to TCP.
- REMOTE_IPS: this variable has the total number of IPs connected to the honeypot.
- APP_BYTES: this is the number of bytes transfered.
- SOURCE_APP_PACKETS: packets sent from the honeypot to the server.
- REMOTE_APP_PACKETS: packets received from the server.
- APP_PACKETS: this is the total number of IP packets generated during the communication between the honeypot and the server.
- DNS_QUERY_TIMES: this is the number of DNS packets generated during the communication between the honeypot and the server.
- TYPE: this is a categorical variable, its values represent the type of web page analyzed, specifically, 1 is for malicious websites and 0 is for benign websites.