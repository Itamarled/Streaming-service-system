# Streaming-service-system
C++ program that Simulates a streaming service and offers to the users streaming content by the Algorithm that chosen by the user when created.


Run Instructions:
g++ -g -Wall -c -Include src/main.cpp src/Action.cpp src/Session.cpp src/User.cpp src/Watchable.cpp

g++ -o splflix.exe src/main.cpp src/Action.cpp src/Session.cpp src/User.cpp src/Watchable.cpp

 splflix.exe config2.json
 
 
 
 On Linux:
 make
 ./bin/splflix config2.json