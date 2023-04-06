# SQL-ODEV8

## 1.test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

CREATE TABLE employee (id INTEGER PRIMARY KEY,
name VARCHAR(50) NOT NULL,
birthday DATE,
email VARCHAR(100) );

## 2.Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
Preview
insert into employee (id, name, birthday, email) values (1, 'Arron', null, 'ahendricks0@networksolutions.com');
insert into employee (id, name, birthday, email) values (2, 'Scarlet', '2022-05-26', 'sdowbiggin1@apple.com');
insert into employee (id, name, birthday, email) values (3, 'Lonnard', null, 'lpenrice2@miitbeian.gov.cn');
insert into employee (id, name, birthday, email) values (4, 'Colette', '2022-04-20', 'cbanfield3@nba.com');
insert into employee (id, name, birthday, email) values (5, 'Morganica', '2022-06-23', 'mrockey4@oracle.com');
insert into employee (id, name, birthday, email) values (6, 'Gracie', '2022-10-05', 'gcastagneto5@networksolutions.com');
insert into employee (id, name, birthday, email) values (7, 'Abbott', '2022-09-09', 'aambrogi6@msu.edu');
insert into employee (id, name, birthday, email) values (8, 'Bald', '2022-12-14', 'bgleadhell7@yellowpages.com');
insert into employee (id, name, birthday, email) values (9, 'Jaquelin', null, 'jhatterslay8@ameblo.jp');
insert into employee (id, name, birthday, email) values (10, 'Lucie', '2022-05-04', 'lriddoch9@slate.com');
insert into employee (id, name, birthday, email) values (11, 'Josepha', '2022-04-06', 'jbraccia@theatlantic.com');
insert into employee (id, name, birthday, email) values (12, 'Archambault', '2022-09-19', 'aaugerb@naver.com');
insert into employee (id, name, birthday, email) values (13, 'Artemis', '2023-01-28', 'ascophamc@list-manage.com');
insert into employee (id, name, birthday, email) values (14, 'Brett', '2022-08-29', 'bdoddingd@infoseek.co.jp');
insert into employee (id, name, birthday, email) values (15, 'Roderic', '2022-11-21', 'rrohlfinge@marriott.com');
insert into employee (id, name, birthday, email) values (16, 'Harris', '2023-03-08', 'hfaulderf@unesco.org');
insert into employee (id, name, birthday, email) values (17, 'Gerry', null, 'gbooneg@harvard.edu');
insert into employee (id, name, birthday, email) values (18, 'Kinnie', null, 'kgreweh@quantcast.com');
insert into employee (id, name, birthday, email) values (19, 'Gasper', null, 'gzouchi@wordpress.org');
insert into employee (id, name, birthday, email) values (20, 'Clemmie', '2022-05-26', 'ccatfordj@google.com.hk');
insert into employee (id, name, birthday, email) values (21, 'Alidia', '2023-03-01', 'alerouxk@ask.com');
insert into employee (id, name, birthday, email) values (22, 'Lorens', '2023-01-20', 'lgrederl@squarespace.com');
insert into employee (id, name, birthday, email) values (23, 'Hodge', '2022-05-01', 'hrobackm@creativecommons.org');
insert into employee (id, name, birthday, email) values (24, 'Augusto', '2023-02-27', 'achristalln@noaa.gov');
insert into employee (id, name, birthday, email) values (25, 'Marijo', '2022-10-03', 'mkornilovo@soup.io');
insert into employee (id, name, birthday, email) values (26, 'Rowen', '2022-05-05', 'rwillimontp@guardian.co.uk');
insert into employee (id, name, birthday, email) values (27, 'Sasha', '2023-01-10', 'sjohannq@feedburner.com');
insert into employee (id, name, birthday, email) values (28, 'Sheree', '2022-08-23', 'sohartnedyr@ocn.ne.jp');
insert into employee (id, name, birthday, email) values (29, 'Kent', '2022-09-26', 'kbenedyktowiczs@hc360.com');
insert into employee (id, name, birthday, email) values (30, 'Broddy', '2023-02-12', 'bsuermeierst@bloglines.com');
insert into employee (id, name, birthday, email) values (31, 'Dani', '2022-06-17', 'drowbottomu@squarespace.com');
insert into employee (id, name, birthday, email) values (32, 'Farleigh', '2023-01-21', 'fmollettv@ted.com');
insert into employee (id, name, birthday, email) values (33, 'Brina', '2023-02-26', 'bzimmermeisterw@i2i.jp');
insert into employee (id, name, birthday, email) values (34, 'Kile', '2022-11-05', 'kcolganx@artisteer.com');
insert into employee (id, name, birthday, email) values (35, 'Sylvester', '2022-10-12', 'sbarsamy@pagesperso-orange.fr');
insert into employee (id, name, birthday, email) values (36, 'Tedra', '2023-02-09', 'tdessonz@odnoklassniki.ru');
insert into employee (id, name, birthday, email) values (37, 'Rica', '2023-03-05', 'rbarron10@ft.com');
insert into employee (id, name, birthday, email) values (38, 'Correy', '2022-05-26', 'cdomenge11@ovh.net');
insert into employee (id, name, birthday, email) values (39, 'Katleen', '2023-03-27', 'kstansbury12@ft.com');
insert into employee (id, name, birthday, email) values (40, 'Dane', '2022-10-17', 'dsmithend13@sina.com.cn');
insert into employee (id, name, birthday, email) values (41, 'Charlean', '2022-07-17', 'cgwilliams14@webmd.com');
insert into employee (id, name, birthday, email) values (42, 'Cody', '2023-01-10', 'cnealey15@telegraph.co.uk');
insert into employee (id, name, birthday, email) values (43, 'Philippe', '2022-11-03', 'pgleder16@parallels.com');
insert into employee (id, name, birthday, email) values (44, 'Vittoria', null, 'vesslement17@arstechnica.com');
insert into employee (id, name, birthday, email) values (45, 'Eduardo', null, 'ebarber18@networkadvertising.org');
insert into employee (id, name, birthday, email) values (46, 'Randi', '2022-10-02', 'romolan19@github.com');
insert into employee (id, name, birthday, email) values (47, 'Kassey', '2022-09-23', 'kbreewood1a@gravatar.com');
insert into employee (id, name, birthday, email) values (48, 'Doralia', '2022-04-09', 'dbutterworth1b@oakley.com');
insert into employee (id, name, birthday, email) values (49, 'Marven', '2022-04-18', 'mbellerby1c@paginegialle.it');
insert into employee (id, name, birthday, email) values (50, 'Agosto', '2022-10-23', 'awimbury1d@123-reg.co.uk');

## 3.Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

UPDATE employee
SET name = 'Alex'
WHERE name = 'Marven';

UPDATE employee
SET email = 'null'
WHERE id > 46;

UPDATE employee
SET name = 'Max',
birthday = '2022-10-8',
email = 'max@gamil.com'
WHERE id = 50;

UPDATE employee
SET birthday = '2022-12-12'
WHERE birthday = '2022-09-23';

UPDATE employee
SET name = 'XXX'
WHERE name LIKE 'A%';

## 4.Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

DELETE FROM employee
WHERE id BETWEEN 25 AND 30;

DELETE FROM employee
WHERE name ='Randi';

DELETE FROM employee
WHERE birthday = '2022-07-17';

DELETE FROM employee
WHERE id = 6;

DELETE FROM employee
WHERE email = 'kbreewood1a@gravatar.com';
