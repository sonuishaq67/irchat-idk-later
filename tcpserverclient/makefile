default:
		gcc -pthread tcpclient.c -o client
		gcc -pthread tcpserver.c -o server
		./server & ./client
clean:
		rm client server