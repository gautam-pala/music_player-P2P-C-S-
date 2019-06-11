# project1
Basically, In This Music Player, we are going to use Python socket
programming as part of computer networks course. socket
programming does not provide us the power to play any sound file.
Therefore for playing any sound file, we have to take help from a
third party module called the mpg123.
o In Simple Words, To make any music player using module socket,
threading, time and mpg123 library. You Just Need To Create A
Function That Can Handle And Play All Provided Music Files.
o We divided all Coding functions and problems into Small Modules
and after creating all function in the separate script we just combine
all together to make a powerful program.
o In this project, when peer connects to server, at that time server
send the music list which is present in it and it maintains the peers
list of existing peers. so peer will see that which songs server have.
If a peer sends the music request to the server, the server will see
own music list if music will present in that then server divides the
whole music into small chunks and chunks will send from server to
client. In the client side, there is a buffer, in that buffer chunks will
store and will play the music by using mpg123 library
simultaneously.
o If the music does not present on the server music list, then the
server will check the music in all peers which are connected with it.
If any other peer has that music then the server will send the
address of that peer which have that music to the peer which send
music request.
2o And after that peer will send the music to that peer. If no one peer
has that music or no one have a connection with the server, then
the server will send the false statement to the peer which send the
music request.
o When one peer sends the music to the other peer, at that time peer
which send the music to send the music request to the server, then
the server will send the music if it has otherwise it will check the
music in the all existing peers. And other peers who receive the
music from that peer and playing that music send the music to that
peer which send the music request while playing the song. Means
simultaneously send and receive music will be done.
o When a new peer connects to the server, at that time server send
the music list which it has and it adds the peer address in peers list
which server has. When the client sends the music request to the
server, the server will check that music in own music list if not then
it will check the music in all peers. And if anyone peer has that
music then the server sends the address of that peer. And peer to
peers sharing will be done And that’s all.
