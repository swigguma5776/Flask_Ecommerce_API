# Flask_Ecommerce_API
Developing an e-commerce RESTful API in Flask that emulates admin users creating &amp; managing shop items &amp; frontend client/customer order requests. 

### Create Virtual Environment:
- Windows
  - 'python -m venv <name_of__env>'
- Mac
  - 'python3 -m venv <name_of_env>'

### Open Virtual Environment:
- Windows
  - '<name_of_env>\Scripts\activate'
- Mac
  - 'source <name_of_env>/bin/activate'
 
### Install packages:
  - run 'pip install -r requirements.txt' in terminal (pip3 for mac)

### Connect Database:
  - if creating Database in SQL
    - create database & copy connection string
    - create an .env file
    - create DATABASE_URL variable and set equal database connection string (make sure to add sq at the end of postgres)
   
  - run following commands in terminal
    -  flask db init
    -  flask db migrate -m "message" (will default to SQLlite if no database is connected)
    -  flask db upgrade

### Run Flask App:
  - run 'flask run' in terminal 


  
