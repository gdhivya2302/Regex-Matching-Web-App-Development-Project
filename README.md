 Regex Matching Web App Development Project

 After creating an instance, the steps for adding commands in the command prompt are as follows:
 
    1.ssh -i "regex_match_pattern.pem" ubuntu@ec2-54-167-123-42.compute-1.amazonaws.com
    2.pwd
    3.ls
    4.logout
    5.scp -r -i "regex_match_pattern.pem" webapp ubuntu@ec2-54-167-123-42.compute-1.amazonaws.com
    6.ssh -i "regex_match_pattern.pem" ubuntu@ec2-54-167-123-42.compute-1.amazonaws.com
    7.sudo apt update
    8.sudo apt upgrade
    9.sudo apt install python3-pip
    10.pip list
    11.ls
    12.cd webapp/
    13.pip install -r requirements.txt
    14.python3 app.py
    15.nohup python3 app.py &
