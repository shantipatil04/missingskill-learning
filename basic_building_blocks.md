<br>
<br>
<div style="text-align: center">

# **Basic Building Blocks of Web Application Development**


</div> 
<br>      

<div style="text-align: justify">  

<font size="4">
<u>

## **IP Address:**

</u>

IP Address stands for Internet Protocol Address. An IP address is a Unique address Assigned to each device. IP Address allows other devices to identify and connect to the device at the IP address. Without IP Address no application can work. It helps the device to connect to other devices. If we type the command dig google.com then it gives the IP address of Google.

### **Two Version of Ip address:** 

- **IPv4 :** 
IPv4 is a 32-bit IP address that uniquely identifies the network.IPv4 is a numeric address separated by the (.).It is very popular in networking.

- **Ipv6 :**
IPv6 is a 128-bit IP Address. It is a most recent version of Internet Protocol.IPv6 is an alphanumeric address separated by (:).

### **Classification of IP:**

* **Class A:** 

    It is used for a large number of the host.
Range: 0-127 i.e.,[ 0.0.0.0 - 127.255.255.255 ].
127 is reserved for the local system.
10-10.255 [local]
 
* **Class B:**
 
    It is used for medium-size network.
Range: 128-191 i.e., [ 128.0.0.0 - 191.255.0.0 ].

* **Class C:**

    It is used for the Local Area network.
Range: 192-223 i.e., [ 192.0.0.0-223.255.255.0 ] .
It is a local network IP.

* **Class D:**

    It is reserve for multitasking.
Range: 224-239 i.e.,[ 224.0.0.0 - 239.255.255.255 ].
It is not used. It is a reserved address.

* **Class E:**

    Range: 240-255 i.e.,[ 240.0.0.0 - 255.255.255.255 ].
It is also not in use. It is used for research purposes.



### **Types of IP Address:**

* **1.Public:** 

    In this, each of the connected devices has the same IP address.

* **2.Private:** 

     The private Ip address is the unique address assigned to each device that connects to the internet. It is used internally within the organization.

* **3.Dynamic:** 

     Dynamic Ip address is a temporary address and it always keeps changing.

* **4.Static:**

     Static Ip address is the address that cannot be changed. Static Ip addresses are generally used by the servers.

<u>

## **Port:**

</u>

Browsers internally convert the domain name into the Ip Address and Port. Port number is also like addressing the information to identify the senders and receivers of the message.

There are 65535 possible port numbers,
* 0-1023 is the reserved port used by the system.

* 1024-49151 are the registered port number. It is an application port. We normally
 used 3000-9999.
* 49152-65536 are used as private port or open port means they can be used by anybody.

<u>

## **Web port:**

</u>

It uniquely identifies the transaction over a network. Normally we use the HTTP or HTTPS protocol i.e., the port numbers 80 and 443. Both are used for the transaction process. HTTPS is more secure than HTTP. So, All the production applications are run on 443 i.e., HTTPS.

<u>

## **Web Servers:**

</u>


 Web Servers are nothing but the kind of application where your web applications are hosted. Web servers is a computer that runs websites. It is computer software and hardware that accepts requests via HTTP.Examples: Apache 2.0,Nginx, Lighthttpd etc.

<u>

## **HTTP Verbs:** 

</u>

The Primary or most commonly used HTTP verbs: GET, POST, PUT, DELETE, OPTION, HEAD.

* **GET:** The HTTP GET method is used to read or retrieve the data. IT is used for fetching the data.

* **POST:** It is used for sending data to the server or used for creating new resources.

* **PUT:** PUT is used to send the data to a server to create /update the resources.

* **DELETE:** The HTTP DELETE method is used to delete a resource from the server.

* **OPTION:** It is used to request information about the communication option available for the resource.

* **HEAD:** It is used to request HTTP headers from the server.

<u>

## **HTTP Headers:**

</u>

The header is a kind of definition that the browser is sending or any application sending to the server based on that server may or may not decide to do something. This is heavily used when we working in web applications for passing any data, checking authentication, passing some keys, etc.

<u>

## **HTTP Status Code:**

</u>

 HTTP status is issued by a server in response to a client’s request made to the server.
* **100:**  The initial part of the request has been received and has not yet been rejected by the server.

* **200:** It indicates that the request has succeeded.

* **300:** It is required for kind of migration. It indicates that resources are temporarily located to another URL.

* **400:** It is used for user authentication or user checked.

* **500:** It indicates the server-side problem. Application not working, Application crash, etc.

<u>

## **Software License:**

</u>

A software license is a contract between the entity that created and supplies an application, underlying source code and its end-user. It also provides a legally binding definition for the distribution and use of the software. Examples, Apache 2.0, MIT, GPL, BSD, Mozilla, etc.

<u>

## **Database:**

</u>

The database is a data structure that stores organized information. It is a collection of information that is organized so that it can be easily accessed, managed, and updated.

Two Types of Database: 
Relational Database and Non-Relational Database.

* Relational database a structure that allows us to identify and access data in relation to another piece of data in a database.examples, MySQL, MariaDB, PostgreSQL etc.
* Non-Relational Database does not use the tabular schema of rows and columns. It uses a storage model that is optimized for specific requirements. Examples, MongoDB, Redis, Neo4j, Cassandra, etc.

<u>

## **Cloud Provider:**

</u>

Using cloud Providers is a helpful way to access computing services.

Components are,
* Infrastructure-as-a-service(Iaas)
 
* Platform-as-a-Service(Paas) 
* Software-as-a-Service(Saas)

Examples: Amazon Web Servies (AWS), Google, DigitalOcean, Linode, etc.

<u>

## **Code Repository:**

</u>

A code repository is where patches of source code for software programs are archived in an organized way. Tools are, GitHub, GitLab, Bitbucket etc.

<u>

## **Git Development Workflow:**

</u>

It is a basic workflow for developing a simple website. They are done in the following branches:1. Feature Branch must have when you have more than one developer working on the same code, 2. Develop Branch reflects the state with the latest changes for the next release,3. Stage Branch, 4.Master Branch(Deployed to production) always reflects a production-ready state.

</font>

</div>