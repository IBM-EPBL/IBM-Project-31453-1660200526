create table userdetails(

		uid integer unique not null GENERATED ALWAYS AS IDENTITY (START WITH 1 INCREMENT BY 1),
		rollno integer unique not null,
		username varchar(30) unique not null,
		email varchar(40) unique not null,
		password varchar(8) unique not null
		)