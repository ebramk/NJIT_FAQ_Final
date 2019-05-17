NJIT FAQ SYSTEM

This project was created to allow NJIT students to post different questions and even answer questions. This application was built on the Laravel framework and deployed to the Heroku. The database was built on SQLITE and turned into a Postgres database in order to work on Heroku. This web app also verifies users by sending a secure verification email to eliminate spam users. The verification runs using a remote SMPT server. 

Project link on Heroku: http://njit-601-faq.herokuapp.com/
Project GitHub link: https://github.com/ebramk/NJIT_FAQ_Final
Demo Video: https://drive.google.com/file/d/1BGys8GTIdUdlRYVr68GcxoNUfDWrzTym/view
How to run: 
1.	Clone the project 
2.	cd to faq and run composer install
3.	Copy .env.example to .env
4.	php artisan key:generate
5.	Setup database 
6.	Run: php artisan migrate
7.	Run: unit tests: phpunit
8.	7 Run: seeds php artisan migrate:refresh --seed
Epic:  To ensure the overall security of the website and improve of the user experience.

User case 1: As a user of NJIT’s FAQ system, I would like to know that only real users have access to the website. 

User case 2: Prevent spammers from registering to the system and answering random questions. 

User case 3: As a user of NJIT’s FAQ system, I would like the website to remain fast and responsive. 

User case 4: As a user of the NJIT FAQ application I would like to know that malicious users on the website could be removed if need or if reported to the admins.
 
