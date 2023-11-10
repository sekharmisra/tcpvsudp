# tcpvsudp
TCP vs UDP protocol Example


# Step 1 - Init the project: npm init (Generates package.json)
# Step 2 - Add net package npm install -D net
# Step 3 - Add nodemon package npm install -D nodemon
# Step 4 - Install Telenet client from Windows Feature (Executed code in Windows Machine)
# Step 5 - Start debugging and put breakpoin on the logging and see result & stop debugging
    Microsoft Telnet> open 127.0.0.1 8080
    Connecting To 127.0.0.1...
    Hello from TCP Server! 
    Connection to host lost.
    Connection closed by the host
    Microsoft Telnet> open 127.0.0.1 8080
    Connecting To 127.0.0.1...Could not open connection to the host, on port 8080: Connect failed

# Step 6 - Start UDP server
# Step 7 - Use MAC UDP client to test the UDP server - echo "hello" | nc -w1 -u 127.0.0.1 41234


