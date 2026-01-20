**Definition** : A program which is runs the web server and it can be accessed from the browser is called Web Application. Web is a space where application are get connected and interacted

Example : CyberChef, Gmail, Github etc. 


## 1. HTTP and HTTPS : 
These are a main protocol(set of rules) which is used for communication between client(browser) and the web server.

**HTTP** (HyperText Transfer Protocol) :  The data send is not encypted so anybody who intercept the request can see the data. Hence it is not secure. It is slightly faster since it doesn't spend time encrypting and decrypting data. Developers often use HTTP in local environment becasue it's easier to setup. 

**HTTPS** (HyperText Transfer Protocol Secure) : Encrypts the data so even if they intercept they can't understand it will be in a Gibberish. HTTPS uses SSL/TLS protocol to encrypt the data and make the connection secure. Used almost everywhere example : https://google.com.

## 2. SSL/TLS :

SSL(secure socket layer) : When a browser request for a connection and CA(Certifacte Authority) to the server. The server provides it CA(which the domain name, exipre date etc.) aand browser checks it is valid and not and then if it correct and valid both agreed to use a secret key for encryption and now all data send from the server to the browser is encrypted hence no one can read it even if they inctercept that. This is how SSL works for security. 

TLS(Transport Layer Security) : It is upgrade version of the SSL. It provide strong encryption and better handshake and integrity. 

# 3. TCP/IP : 

TCP(Transmission Control Protocol) :  It is a connection oriented protocol for reliable connection over internet. It splits data into packets and sends to the destination. and it checks for error and it uses three-way hanshake(SYN, SYN-ACK, ACK) and establish a connection before sending the data. Example : Loading a website, sending an email. 

IP(Internet Protocol) : It is newtwork layer protocol and connectionless which handles addressing and routing of data packets each device on the network has the IP address. 






