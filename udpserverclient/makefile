default:
		gcc -pthread udpclient.c -o client
		gcc -pthread udpserver.c -o server
		./server & ./client
clean:
		rm client server