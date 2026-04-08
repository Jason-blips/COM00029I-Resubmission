Question 1
Q1a: Ok.
Q1b: Why can you assume that the latency is half the RTT? It's also worth noting that the question provides the ip addresses for different universities, and asks which of these university servers is not hosted in their respective country.
Q1c: Note that the reduced speed of light in optical fibre is already accounted for in the assumed speed of light given in the question, but the other explanations are valid.
Q1d: Code builds fine, output is correct. For loop is sensible. Loop variable type should be uint_fast8_t or perhaps uint8_t. Loop is compact.


Question 2
Q2a: Answer file contains extraneous non-bob information.
Q2b: Ok .
Q2c: Not fully answered, missing packet capture, invalid email address, code will not function correctly.
Q2d: Output is correct. Code is good. Union accesses appropriate.


Question 3
Q3a: Ok.
Q3b: Does not answer the question set i.e. not resolved by lab server.
Q3c: Good.
Q3d: Does not answer the question set i.e. libs used, will process unicast, .
Q3e: Memory leaks reported correctly. Invalid free() reported correctly. Divergence from requested towards simpler scenario.


Question 4
Q4a: Answer file does not match with the submitted packet capture.
Q4b: Can not open pcap files.
Q4c: IP/Ports not correct, will not work.
Q4d: IP not correct will not work.
Q4e: File created with correct permissions. Generated text file doesn't match the submitted one (lengths differ, 134 vs 135).


Question 5
Q5a: Packet capture does not appear to show a connection to the cowsay server. Submitted filter does not filter for a three-way handshake. Discussion about values advertised by Pi2 and Pi3 during a three way handshake does not refer to observed values in a packet capture.
Q5b: The highlighted packet is not a wrapped HELLO message from Pi-1.
Q5c: Need to be more specific, what caused these packets to occur i.e. what happened on the pi to cause these packets.
Q5d: What did you change such between the first set of successful connections that generated FIN packets and the second set where the connection was refused?
Q5e: Make it a habit to unmap mapped memory after use, in both forked processes. By generating the random number before forking you have undermined the point of the exercise. Parent process prints PID and random number ok. Child process prints PID and random number ok.


Question 6
Q6a: Correct.
Q6b: Tcptrace graph does not show a delayed ACK, filter does not select a delayed ACK packet and its related data packets, .
Q6c: Expected more packets matching tcp.port==1234 in the captures, 600kB should have been transferred. Your packet counts are off (you included the VNC packets). If you run it several times you should find that Python buffer size and packet size are unconnected, TCP is a stream protocol.
Q6d: Ok, but filter did not remove unrelated packets, .
Q6e: Code structure is correct, mutexes used as requested. didn't produce the most explicit error message because of how the mutex was initialised. Helgrind report for recursive mutex code is correct.


Question 7
Q7a: Pcap does not contain a single large UDP packet.
Q7b: Ok.
Q7c: Ok, but how does this change affect the existing subnets?
Q7d: Instructions not followed - there should be three tasks in this submission and there's only one. The ISR won't run either.


Question 8
Q8a: Missing direct broadcast.
Q8b: Incorrect number.
Q8c: Some errors in discussion of differences.
Q8d: Correct.
Q8e: You were instructed to extend your program from the lab, which used the read() and write() syscalls - this was the point of the exercise.


Question 9
Q9a: Correct.
Q9b: Packet capture does not show successful ping of the lab’s NTP time server / associated ARP packets. Discussion is not entirely correct.
Q9c: Correct.
Q9d: No PCAP file submitted. Incomplete submissions cannot be marked.