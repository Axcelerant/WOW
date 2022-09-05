This guide assumes you have node installed on unix


SO we want to run server.js and survive terminal close

How to survive terminal close

1. node server.js & disown

This will disown the node server so that it survives terminal close and return the process ID

how to access process id and terminate the node app

find all running node processes
ps -e|grep node

lists
195807 ?        00:00:37 node



ps --quick-pid 195807



ps -ef|grep node 
displays name is the best option imo