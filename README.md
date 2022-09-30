# MySQL-project

create database IPL_Data_Management;

use IPL_data_management;

create table Player_Data(
Player_id int not null,
Player_name varchar(30),
Age int not null,
Country varchar(30));

select * from Player_Data;

insert into Player_Data
values(1,'MAYANK AGARWAL',31,'INDIA');

insert into Player_Data
values(2,'SHIKHAR DHAWAN',36,'INDIA'), (3,'RAHUL CHAHAR',23,'INDIA'), (4,'JONNY BAIRSTOW',33,'ENGLAND'),
(5,'KAGISO RABADA',27,'SOUTH AFRICA'), (6,'ARSHDEEP SINGH',23,'INDIA'),(7,'NATHAN ELLIS',27,'AUSTRALIA'),
(8,'RAJ ANGAD BAWA',19,'INDIA'), (9,'ODEAN SMITH',25,'JAMAICA'), (10,'HARPREET BRAR',26,'INDIA'),
(11,'KANE WILLIAMSON',32,'NEW ZEALAND'), (12,'RAHUL TRIPATHI',31,'INDIA'), (13,'BHUVNESHWAR KUMAR',32,'INDIA'),
(14,'T NATARAJAN',31,'INDIA'), (15,'NICHOLAS POORAN',26,'WEST INDIES'), (16,'ABHISHEK SHARMA',22,'INDIA'),
(17,'GLENN PHILIPS',25,'NEW ZEALAND'), (18,'SEAN ABBOTT',30,'AUSTRALIA'), (19,'SHREYAS GOPAL',29,'INDIA'),
(20,'UMRAN MALIK',22,'INDIA'), (21,'SANJU SAMSON',27,'INDIA'),(22,'JOS BUTTLER',32,'ENGLAND'),
(23,'PRASIDH KRISHNA',26,'INDIA'), (24,'TRENT BOULT',33,'NEW ZEALAND'), (25,'YUZVENDRA CHAHAL',32,'INDIA'),
(26,'SHIMRON HETMYER',25,'WEST INDIES'), (27,'DEVDUTT PADIKKAL',22,'INDIA'), (28,'RIYAN PARAG',20,'INDIA'),
(29,'NAVDEEP SAINI',29,'INDIA'), (30,'KULDEEP YADAV',27,'INDIA'), (31,'DARYL MITCHELL',31,'NEW ZEALAND'),
(32,'R ASHWIN',36,'INDIA'), (33,'VIRAT KOHLI',33,'INDIA'), (34,'GLENN MAXWELL',33,'AUSTRALIA'),
(35,'HARSHAL PATEL',31,'INDIA'), (36,'JOSH HAZLEWOOD',31,'AUSTRALIA'),(37,'FAF DU PLESIS',38,'SOUTH AFRICA'),
(38,'MOHAMMED SIRAJ',28,'INDIA'), (39,'DINESH KARTHIK',37,'INDIA'), (40,'WANINDU HASARANGA',25,'SRI LANKA'),
(41,'ANUJ RAWAT',22,'INDIA'), (42,'AKASH DEEP',25,'INDIA'), (43,'FINN ALLEN',23,'NEW ZEALAND'),
(44,'ROHIT SHARMA',35,'INDIA'), (45,'ISHAN KISHAN',24,'INDIA'), (46,'JASPRIT BUMRAH',28,'INDIA'),
(47,'KIERON POLLARD',35,'WEST INDIES'), (48,'DEWALD BREVIS',19,'SOUTH AFRICA'), (49,'MURUGAN ASHWIN',32,'INDIA'),
(50,'TILAK VERMA',19,'INDIA'), (51,'SURYAKUMAR YADAV',32,'INDIA'),(52,'TIM DAVID',26,'AUSTRALIA'),
(53,'MS DHONI',41,'INDIA'), (54,'RAVINDRA JADEJA',33,'INDIA'), (55,'DEEPAK CHAHAR',30,'INDIA'),
(56,'MOEEN ALI',35,'ENGLAND'), (57,'AMBATI RAYUDU',37,'INDIA'), (58,'RUTURAJ GAIKWAD',25,'INDIA'),
(59,'DWAYNE BRAVO',38,'WEST INDIES'), (60,'KM ASIF',29,'INDIA'), (61,'ADAM MILNE',30,'NEW ZEALAND'),
(62,'MITCHELL SANTNER',30,'NEW ZEALAND'), (63,'CHRIS JORDAN',33,'ENGLAND'), (64,'SHREYAS IYER',27,'INDIA'),
(65,'ANDRE RUSSELL',34,'WEST INDIES'), (66,'NITISH RANA',28,'INDIA'),(67,'VENKATESH IYER',27,'INDIA'),
(68,'PAT CUMMINS',29,'AUSTRALIA'), (69,'SUNIL NARINE',34,'WEST INDIES'), (70,'AJINKYA RAHANE',34,'INDIA'),
(71,'SHELDON JACKSON',35,'INDIA'), (72,'ANUKUL ROY',23,'INDIA'), (73,'UMESH YADAV',34,'INDIA'),
(74,'RASIKH DAR',22,'INDIA'), (75,'RISHABH PANT',24,'INDIA'), (76,'SHARDUL THAKUR',30,'INDIA'),
(77,'AXAR PATEL',28,'INDIA'), (78,'PRITHVI SHAW',22,'INDIA'), (79,'MITCHELL MARSH',30,'AUSTRALIA'),
(80,'DAVID WARNER',35,'AUSTRALIA'), (81,'KULDEEP YADAV',27,'INDIA'),(82,'KHALEEL AHMED',24,'INDIA'),
(83,'SRIKAR BHARAT',28,'INDIA'), (84,'SARFARAZ KHAN',24,'INDIA'), (85,'KL RAHUL',30,'INDIA'),
(86,'AVESH KHAN',25,'INDIA'), (87,'MARCUS STOINIS',33,'AUSTRALIA'), (88,'JASON HOLDER',30,'WEST INDIES'),
(89,'KRUNAL PANDYA',31,'INDIA'), (90,'MARK WOOD',32,'ENGLAND'), (91,'QUINTON DE KOCK',29,'SOUTH AFRICA'),
(92,'DEEPAK HOODA',27,'INDIA'), (93,'MANISH PANDEY',33,'INDIA'), (94,'RAVI BISHNOI',32,'INDIA'),
(95,'MOHSIN KHAN',24,'INDIA'), (96,'RASHID KHAN',24,'AFGHANISTAN'),(97,'HARDIK PANDYA',28,'INDIA'),
(98,'LOCKIE FERGUSON',31,'NEW ZEALAND'), (99,'RAHUL TEWATIA',29,'INDIA'), (100,'SHUBHMAN GILL',23,'INDIA'),
(101,'MOHAMMED SHAMI',32,'INDIA'), (102,'JASON ROY',32,'ENGLAND'), (103,'JAYANT YADAV',32,'INDIA'),
(104,'VIJAY SHANKAR',31,'INDIA'), (105,'ABHINAV MANOHAR',28,'INDIA'), (106,'DAVID MILLER',33,'SOUTH AFRICA');

select * from Player_Data;

create table Team_Data(
Serial_no int not null,
Player_role varchar(50),
Jersey_no int not null,
IPL_Team varchar(10),
Sold_price_in_crores float not null);

insert into Team_Data
values(1,'BATSMAN',16,'PK',12);

insert into Team_Data
values(2,'BATSMAN',42,'PK',8.25), (3,'BOWLER',28,'PK',5.25), (4,'BATSMAN/WICKET KEEPER',51,'PK',6.75),
(5,'BOWLER',25,'PK',9.25), (6,'BOWLER',2,'PK',4),(7,'BOWLER',12,'PK',0.75),
(8,'BATSMAN',12,'PK',2), (9,'BATSMAN',15,'PK',6), (10,'BATSMAN',95,'PK',3.8),
(11,'BATSMAN',22,'SRH',14), (12,'BATSMAN',52,'SRH',8.5), (13,'BOWLER',15,'SRH',4.2),
(14,'BOWLER',44,'SRH',4), (15,'BATSMAN',29,'SRH',10.75), (16,'ALL-ROUNDER',4,'SRH',6.5),
(17,'BATSMAN/WICKET KEEPER',23,'SRH',1.5), (18,'BOWLER',77,'SRH',2.4), (19,'BOWLER',37,'SRH',0.75),
(20,'BOWLER',98,'SRH',4), (21,'BATSMAN/WICKET KEEPER',9,'RR',14),(22,'BATSMAN',63,'RR',10),
(23,'BOWLER',24,'RR',10), (24,'BOWLER',89,'RR',8), (25,'BOWLER',6,'RR',6.5),
(26,'BATSMAN',189,'RR',8.5), (27,'BATSMAN',37,'RR',7.75), (28,'ALL-ROUNDER',3,'RR',3.8),
(29,'BOWLER',96,'RR',2.6), (30,'BOWLER',23,'RR',0.20), (31,'BATSMAN',75,'RR',0.75),
(32,'BOWLER',99,'RR',5), (33,'BATSMAN',18,'RCB',15), (34,'ALL-ROUNDER',32,'RCB',11),
(35,'BOWLER',9,'RCB',10.75), (36,'BOWLER',38,'RCB',7.75),(37,'BATSMAN',13,'RCB',7),
(38,'BOWLER',73,'RCB',7), (39,'BATSMAN/WICKET KEEPER',19,'RCB',5.5), (40,'BOWLER',49,'RCB',10.75),
(41,'BATSMAN/WICKET KEEPER',25,'RCB',3.4), (42,'BOWLER',42,'RCB',0.20), (43,'BATSMAN/WICKET KEEPER',16,'RCB',0.80),
(44,'BATSMAN',45,'MI',16), (45,'BATSMAN',32,'MI',15.25), (46,'BOWLER',93,'MI',12),
(47,'ALL-ROUNDER',55,'MI',6), (48,'BATSMAN',17,'MI',3), (49,'BOWLER',89,'MI',1.6),
(50,'BATSMAN',5,'MI',1.7), (51,'BATSMAN',63,'MI',8),(52,'ALL-ROUNDER',85,'MI',1),
(53,'BATSMAN/WICKET KEEPER',7,'CSK',12), (54,'ALL-ROUNDER',8,'CSK',16), (55,'BOWLER',90,'CSK',14),
(56,'ALL-ROUNDER',18,'CSK',8), (57,'BATSMAN/WICKET KEEPER',5,'CSK',6.75), (58,'BATSMAN',31,'CSK',6),
(59,'BOWLER',47,'CSK',4.4), (60,'BOWLER',24,'CSK',0.2), (61,'BOWLER',20,'CSK',1.9),
(62,'BOWLER',74,'CSK',1.9), (63,'BOWLER',34,'CSK',3.6), (64,'BATSMAN',41,'KKR',12.25),
(65,'ALL-ROUNDER',12,'KKR',12), (66,'BATSMAN',27,'KKR',8),(67,'ALL-ROUNDER',25,'KKR',8),
(68,'ALL-ROUNDER',30,'KKR',7.25), (69,'ALL-ROUNDER',74,'KKR',6), (70,'BATSMAN',27,'KKR',1),
(71,'BATSMAN',21,'KKR',0.60), (72,'ALL-ROUNDER',6,'KKR',0.20), (73,'BOWLER',19,'KKR',2),
(74,'BOWLER',39,'KKR',0.20), (75,'BATSMAN/WICKET KEEPER',17,'DC',16), (76,'BOWLER',54,'DC',10.75),
(77,'ALL-ROUNDER',20,'DC',9), (78,'BATSMAN',100,'DC',7.5), (79,'ALL-ROUNDER',8,'DC',6.5),
(80,'BATSMAN',31,'DC',6.25), (81,'BOWLER',23,'DC',2),(82,'BOWLER',13,'DC',5.25),
(83,'BATSMAN/WICKET KEEPER',15,'DC',2), (84,'BATSMAN',97,'DC',0.20), (85,'BATSMAN',1,'LSG',15),
(86,'BOWLER',5,'LSG',10), (87,'ALL-ROUNDER',17,'LSG',11), (88,'ALL-ROUNDER',98,'LSG',8.75),
(89,'ALL-ROUNDER',36,'LSG',8.25), (90,'BOWLER',33,'LSG',7.5), (91,'BATSMAN/WICKET KEEPER',12,'LSG',6.75),
(92,'ALL-ROUNDER',57,'LSG',5.75), (93,'BATSMAN',21,'LSG',4.6), (94,'BOWLER',56,'LSG',4),
(95,'BOWLER',47,'LSG',0.20), (96,'BOWLER',19,'GT',15),(97,'ALL-ROUNDER',33,'GT',15),
(98,'BOWLER',69,'GT',10), (99,'ALL-ROUNDER',14,'GT',9), (100,'BATSMAN',77,'GT',7),
(101,'BOWLER',11,'GT',6.25), (102,'BATSMAN',20,'GT',2), (103,'ALL-ROUNDER',22,'GT',1.7),
(104,'ALL-ROUNDER',3,'GT',1.4), (105,'BATSMAN',18,'GT',2.6), (106,'BATSMAN',10,'GT',3);

select * from Team_Data;

select player_id, player_name
from player_data;

select player_name, country
from player_data
where age>30;

select * from player_data
where country="India";

select player_id, player_name, age
from player_data 
where player_name like 'R%';

select player_role, jersey_no, ipl_team
from team_data
order by jersey_no desc;

select length(player_name), player_name, age, country
from player_data
order by length(player_name);

select player_id, player_name, substring(country,1,3)
from player_data;

select player_role, ipl_team, sold_price_in_crores
from team_data
where player_role="batsman" or player_role="batsman/wicket keeper";

select player_role, jersey_no, ipl_team, sold_price_in_crores
from team_data
where ipl_team="csk" and sold_price_in_crores>3
order by sold_price_in_crores desc;

select * from player_data
where age in (22,25,27);

select lower(player_role), lower(ipl_team)
from team_data;

select count(player_id)
from player_data
where age>30 or country='south africa';

select max(sold_price_in_crores), min(sold_price_in_crores)
from team_data;

select sum(sold_price_in_crores)
from team_data
where ipl_team='csk';

select avg(sold_price_in_crores)
from team_data
where player_role='bowler' and ipl_team='mi';

select concat(player_name,'-', age) as name_and_age
from player_data;

select * from player_data
where age in (select age from player_data
where age>22);

select player_data.player_name, player_data.country, team_data.player_role, team_data.jersey_no
from player_data
inner join team_data
on player_data.player_id=team_data.serial_no;

select player_data.player_name, player_data.country, team_data.player_role, team_data.jersey_no
from player_data
left join team_data
on player_data.player_id=team_data.serial_no;

select player_data.player_name, player_data.country, team_data.player_role, team_data.jersey_no
from player_data
right join team_data
on player_data.player_id=team_data.serial_no;

select player_data.player_name, player_data.country, team_data.player_role, team_data.jersey_no
from player_data
left join team_data
on player_data.player_id=team_data.serial_no
union
select player_data.player_name, player_data.country, team_data.player_role, team_data.jersey_no
from player_data
right join team_data
on player_data.player_id=team_data.serial_no;

select *
from player_data
left join team_data
on player_data.player_id=team_data.serial_no
union all
select *
from player_data
right join team_data
on player_data.player_id=team_data.serial_no;

create view auction_list_csk as
select player_role, jersey_no, sold_price_in_crores
from team_data
where ipl_team='csk';

select * from auction_list_csk;	
