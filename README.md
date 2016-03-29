# quizjet
How to run it?

(1)Import the database using the sql file "webex21.sql" in the "db file" folder(If the database doesn't exist.).

(2)Import the whole project into Eclipse. 

(3) Configure the database name string "DBNAME" in edu.pitt.pawslab.quizpet.instance.Setting. For example,
"webex21".

(4)Configure db information in the /WEB-INF/web.xml. Configure the url of db.webexURL AND db.user and db.passwd.

(5)Save all the configuration. Run it locally in eclipse to test the project.

(6)Export it as an War file and deploy it on tomcat.
