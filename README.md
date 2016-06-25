1.  Run npm install in both "BarbeQueueForte/client" and "BarbeQueueForte/server"

2.  Install MongoDB 

3.  Create a folder named workshop-7-data in the parent directory of "BarbeQueueForte/". Then, open up the terminal to the directory with "workshop-7-data"

	Start the database with:
	$ mongod --dbpath workshop-7-data
	Note: If you are on Windows, run "C:\Program Files\MongoDB\Server\3.2\bin\mongod.exe" --dbpath workshop-7-data instead.

4.  Run $ npm run watch in "BarbeQueueForte/client" 
5.  Run $ node src/server.js in "BarbeQueueForte/server"