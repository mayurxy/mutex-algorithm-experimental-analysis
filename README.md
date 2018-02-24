# mutex-algorithm-experimental-analysis
README:
---------------------------------------------------------------------------------------------------
Project Name : AOS Final Project
Submitted By : Mayur Talole(mnt150230)
--------------------------------------------------------------------------------------------------
Files and Folders submitted: 
1. TestingImplementation
	- run_test.sh : run to test violations
	- node.log    : log files of all entries of node
	- Test.java   : test code to check for violations in log file

2. Cleanup
	- cleaup.sh   : Kills all the processes started by the net-id specified in configuration file
	- config.txt  : Text file of all machines listed with port numbers

3. RCProtocol
>>Has all java files for executing the Roucairol Carvalho Algorithm Implementation.
	- launcher.sh 	: Does the compilation of .java files, logs into the machines, runs the main program
	- cleanup.sh  	: Kills all the processes started by the net-id specified in configuration file
	- run_test.sh 	: Testing for violations
	- Application.java: Main class file
	- ConfigRead.java : Read from config.txt
	- Message.java	: message type class defination
	- Node.java	: Node class defination class
	- Server.java	: Server implementation
	- Test.java 	: Testing for violation java file
	- TimeStamp.java: Timestamp generation
	- node.log

4. LamportProtocol
>>Has all java files for executing the Lamport Mutual Exclusion Algorithm Implementation.
	- Application.java: Main class file
	- ConfigRead.java : Read from config.txt
	- ClientMessageThread.java
	- Message.java	  : message type class defination
	- Node.java	  : Node class defination class
	- Server.java	  : Server class defination
	- ServerMessageThread.java
	- Test.java:
	- Timestamp.java  : Timestamp generation class
	- launcher.sh	  : Does the compilation of .java files, logs into the machines, runs the main program
	- cleanup.sh 	  : Kills all the processes started by the net-id specified in configuration file
	- run_test.java

5. Project_Report

6. README

------------------------------------------------------------------------------------------------------------------
	
INSTRUCTIONS TO RUN THE PROGRAM

1. Unzip the submitted file
2. Keep the config file, Java files, launcher script in your current working directory.
3. Go into Cleanup directory and add machines into config.txt and run following command:
	./cleanup.sh [config file name][netId]	
3. Go into respective folder of Lamport or RCProtocol folder to run each protocol.
3. Run the launcher script :  
	./launcher.sh [config file name] [netId]
4. Run cleanup script to kill all the processes again as shown in step 3. 
5. In order to test the log data run the following command in same directory where node.log is generated:
	sh run_test.sh
6. Or copy the node.log file into Testingimplementation directory and run the command shown in step 5.
-----------------------------------------------------------------------------------------------------------------


Contact:
for correction and more details contact at mnt150230@utdallas.edu
					   





 
