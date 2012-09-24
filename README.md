HTML-Proxy-Server
=================
This project is a Proxy server and client to help users surfe internet without censorship.
the proxy server must receive plaintext from censored website and encrypt it then send ciphertext to client 
in HTML pages style to prevent DPI catch proxy and drop packets. Client after receiving fake HTML page must try
retrive text content from the page which actually is the ciphertext and then decrypt it to provide censored page...