INFO:root:TIME : 0 

INFO:root: Created a DATA package from host[1] to host[3]
INFO:root: I am host[1] and do not have a route for 3 yet
INFO:root: Host[1] created a RREQ pack to host[3]
INFO:root: I am adding myself to the path
INFO:root: Sending a request to Master from host[1]
INFO:root: Master : the host[1] wants to send a package, has being added for permission

INFO:root:TIME : 1 

INFO:root: Master: Host[1] is allowed to start sending

INFO:root: I am host[1], and I am sending a pack to neighbor[2]
INFO:root: I am host[2] receiving a RREQ id:[1], but I am not the destination
INFO:root: So I (host[2]) must make a broadcast sending to my nighbors
INFO:root: Sending a request to Master from host[2]
INFO:root: Master : the host[2] wants to send a package, has being added for permission

INFO:root:TIME : 2 

INFO:root: Master: Host[2] is allowed to start sending

INFO:root: I am host[2], and I am sending a pack to neighbor[1]
INFO:root: I am host[2], and I am sending a pack to neighbor[3]
INFO:root: I am host[3] and received a RREQ pack from host[1]
INFO:root: Host[3] is sending a RREP to host[1]
INFO:root: Sending a request to Master from host[3]
INFO:root: Master : the host[3] wants to send a package, has being added for permission

INFO:root:TIME : 3 

INFO:root: Master: Host[3] is allowed to start sending

INFO:root: I am host[3], and I am sending a pack to neighbor[2]
INFO:root: I am host[2], received a DATA pack, but is not for me
INFO:root: So I(host[2]) must send to next point
INFO:root: And the next jump is to host[1]
INFO:root: Sending a request to Master from host[2]
INFO:root: Master : the host[2] wants to send a package, has being added for permission

INFO:root: I am host[3], and I am sending a pack to neighbor[10]
INFO:root:TIME : 4 

INFO:root: Master: Host[2] is allowed to start sending

INFO:root: I am host[2], and I am sending a pack to neighbor[1]
INFO:root: I am host[1] and received a RREP from host[3]
INFO:root: So I(host[1]) must send the data pack!
INFO:root: And the next jump is to host[2]
INFO:root: Sending a request to Master from host[1]
INFO:root: Master : the host[1] wants to send a package, has being added for permission

INFO:root: I am host[2], and I am sending a pack to neighbor[3]
INFO:root:TIME : 5 

INFO:root: Master: Host[1] is allowed to start sending

INFO:root: I am host[1], and I am sending a pack to neighbor[2]
INFO:root:I am host[2] receiveing a data pack with id: 0, but is not for me
INFO:root: Sending a request to Master from host[2]
INFO:root: Master : the host[2] wants to send a package, has being added for permission

INFO:root:TIME : 6 

INFO:root: Master: Host[2] is allowed to start sending

INFO:root: I am host[2], and I am sending a pack to neighbor[1]
INFO:root: I am host[2], and I am sending a pack to neighbor[3]
INFO:root: **** Host[3] received a pack from host[1], message is [hello friend 2] ****