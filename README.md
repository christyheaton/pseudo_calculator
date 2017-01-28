#The pseudo_calculator runs a wsgi server on localhost:8090
#The user adds a funtion and argument to the url, and sees a result in the browser

This script was written in Python v3.5
To run, navigate to the location of the script in the command line, then run it with 
python pseudo_calculator.py
Once running, you can call a url like the samples above and see the results

Sample URLS:
http://localhost:8090/positive/5 ==> True
http://localhost:8090/positive/-5 ==> False
http://localhost:8090/negative/87 ==> False
http://localhost:8090/negative/-53 ==> True


