# iot_hackathon
Firstly, we will be creating connection between the client and server through socket programming.

In the given scenario, We mainly have to create an API from python language. 
The client side API has been requesting(GET)[method(i.e. any linux command) and id(unique number which the server must reply in same id)].
The server side API will be providing result(POST) by receiving the request in JSON from client.It will provide the result(code of os command),stdout(standard output of os command),stderr(standard error of os command),id(same as value of id member of request object),errorcode(number for the error).
