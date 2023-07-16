1.Difference between http 1.1 vs http 2
HTTP/1.1

1.Ithe usest works on the textual format.	.
2.There is head of line blocking that blocks all the requests behind it until it doesn’t get its all resources.
3. It uses requests resource Inlining for use getting multiple pages
4.It compresses data by itself.	

HTTP/2
1.It works on the binary protocol
2.It allows multiplexing so one TCP connection is required for multiple requests.
3.It uses PUSH frame by server that collects all multiple pages 
4.It uses HPACK for data compression.



2 Object And its internal representation in JavaScript
          1.Objects in JavaScript may be defined as an unordered collection of related data, of primitive or 
reference types, in the form of “key: value” pairs.
          2.These keys can be variables or functions and are called properties and methods, respectively, in the 
context of an object.

For Eg. If your object is a student, it will have properties like name, age, address, id, etc and methods like updateAddress, updateNam, etc.