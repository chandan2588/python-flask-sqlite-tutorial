Python Flask example application Flaskr using sqlite

1. Install python

2. Install Flask 
   http://flask.pocoo.org/docs/0.10/installation/

3. Download the code. 

4. Create and SET Enviroment Variable 'FLASKR_SETTINGS': 
   export FLASKR_SETTINGS=/home/charlie/Downloads/flaskr-master/FLASKR_SETTINGS.ini
   
5. 'printenv FLASKR_SETTINGS' to see the value

6. Type python to init_db
   -->from flaskr import init_db
   -->init_db() 

7. Run 'Python flaskr.py' from Terminal 

8. If we get error as port already in use then run this below command for whatever port you want to kill: 
   sudo fuser -k 5000/tcp
