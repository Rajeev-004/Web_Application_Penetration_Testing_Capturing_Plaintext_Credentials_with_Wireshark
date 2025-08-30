# Web_Application_Penetration_Testing_Capturing_Plaintext_Credentials_with_Wireshark
This project demonstrates how login credentials can be intercepted using Wireshark from an insecure web application. By capturing HTTP traffic on "testphp.vulnweb.com", we show how usernames and passwords are transmitted in plaintext, highlighting the risks of HTTP and the need for HTTPS encryption.

# About Wireshark

Wireshark is a network protocol analyzer that allows capturing and inspecting packets traveling across a network in real time.
    1. It supports hundreds of protocols (HTTP, TCP, DNS, etc.).
    2. Security researchers use it to detect vulnerabilities, analyze suspicious traffic, and troubleshoot        networks.
    3. In penetration testing, it can reveal sensitive data (like usernames and passwords) when websites use insecure HTTP connections.