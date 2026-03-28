! IMPORTANT: Go to https://gitlab.com/flarewebsite/unblocked for the files

This is a reliable and easy Unblocked Games Site for chromebooks that I made. Even you can host it.
An example that may be blocked for you is https://gavinpooley.org
Here is the steps to host this website yourself:

1. Go to the main branch and select code and download as zip.
2. Go to the web branch and select code and download as zip.
3. Extract them both.
4. Get Laragon for Windows.
5. Put the web folder inside the main folder.
6. Host it on the apache section of Laragon on port 80.
7. Make sure you are port forwarding your device on your website on port 80 and 443.
8. Go to godaddy.com and purchase a domain.
9. On the godaddy Dashboard go to Domain > Dns and add the following records:
- Type: A Name: @ Value:  TTL: Custom > 600 seconds
- Type: A Name: Web Value:  TTL: Custom > 600 seconds.
10. Remove any other type A records there.
11. Download win-acme and create 2 SSL certificates for yourdomain.com and web.yourdomain.com.
12. Make sure the certificates get exported to C:\laragon\etc\ssl.
13. Start apache on Laragon.
14. Go to your new unblocked website.

Gavin Pooley
