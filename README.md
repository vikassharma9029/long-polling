# long-polling
A very simple demonstration of long-polling with AJAX (jQuery) and PHP. Long-polling makes near "real-time" applications possible. in other words it will sends a request to the server, keep the connection open, get an answer when there's "data" for you. This will cost you only one request (per user), but the request keeps a permanent connection between client and server up.

# Purpose 
I wanted to develop notification panel which is automatic refresh without page refresh.

# How to use
Run long-polling.html file : in this file there is an ajax call which will connect our script with server using ajax.
then in server folder there is two file server.php and data.txt
So here whenever notification insert into database i write data.txt file and server.php track the file chage time and gives the response.


