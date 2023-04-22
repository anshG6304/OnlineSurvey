# OnlineSurvey

this project is an Online survey system where user can make a survey form using Java and mysql.

you need to download mysql in order to run the project
run these commands in mysql

CREATE DATABASE survey;

CREATE TABLE actors(id int primary key auto_increment, fname varchar(50), uname varchar(50), pass varchar(50));

CREATE TABLE userQuestions(id int, surveycode varchar(5), total int);

CREATE TABLE questions(surveycode varchar(5), question varchar(255), option1 varchar(255), option2 varchar(255), option3 varchar(255), option4 varchar(255)); 

CREATE TABLE surveyquestions(surveycode varchar(5), qno int, opno int);

