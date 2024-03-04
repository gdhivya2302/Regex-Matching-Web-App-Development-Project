 Regex Matching Web App Development Project

 After creating an instance, the steps for adding commands in the command prompt are as follows:
 
    1.ssh -i "regex_match_pattern.pem" ubuntu@ec2-54-164-112-101.compute-1.amazonaws.com
    2.pwd
    3.ls
    4.logout
    5.scp -r -i "regex_match_pattern.pem" webapp ubuntu@ec2-54-164-112-101.compute-1.amazonaws.com:~/
    6.sudo apt update
    7.sudo apt upgrade
    8.sudo apt install python3-pip
    9.pip list
    10.ls
    11.cd webapp/
    12.pip install -r requirements.txt
    13.python3 app.py
