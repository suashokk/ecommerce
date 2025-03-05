POM.xml

    <parent>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-parent</artifactId>
        <version>3.1.2</version>
        <relativePath/> <!-- Lookup parent from repository -->
    </parent>





for file transfer service 

we can test the API using Postman or cURL.

Using Postman

1. Open Postman.


2. Set the method to POST.


3. Enter the URL:

http://localhost:8081/file/send


4. In the Body tab, select form-data.


5. Add a key:

Key: file

Type: File

Value: Choose a file from your system.
