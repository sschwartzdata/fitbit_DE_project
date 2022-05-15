# Creating sleep_data table in Postgresql

CREATE TABLE sleep_data ( <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   dateOfSleep date NOT NULL, <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   duration int NOT NULL, <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   isMainSleep BOOLEAN NOT NULL, <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	 deepSleep int, <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 	 lightSleep int, <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 	 remSleep int, <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	 wakeSleep int, <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   awakeSleep int, <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	 restlessSleep int, <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 	 asleepSleep int <br>
);
