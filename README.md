# infoblox


This DNS Assessment Script will run 1-1000 DNS queries, in each of the 11 categories, to see how implemented DNS security controls respond.

**Download and Extract the zip file before following the instructions below. 

***NOTE: When asked for a "Sinkhole", enter the IP address of any redirect or sinkhole used in your network. If none, just hit enter. 


In order to run the scripts:

1) Ensure that python is installed on device

2) Open a terminal or command prompt instance at the folder location

3) Type in "python main.py" for Windows and "python3 main.py" for Mac

4) The script will ask questions based on Timeout, Sinkhole, and which tests to run

5) Wait for the results to finish, and you will find results in the "results" folder and a statistics.csv in the working directory
