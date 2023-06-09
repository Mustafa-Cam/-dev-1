### test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
```
create table emplooye(
    id serial PRIMARY KEY,
    name varchar(50) not null,
    email varchar(50)
    birthday date,
)
```

### Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
```
insert into emplooye (id, first_name, email, birthday) values (1, 'Barnabas', 'belletson0@angelfire.com', '7/1/2022');
insert into emplooye (id, first_name, email, birthday) values (2, 'Valida', 'vmatveiko1@bbb.org', '2/27/2023');
insert into emplooye (id, first_name, email, birthday) values (3, 'Orland', 'ospringate2@china.com.cn', '9/26/2022');
insert into emplooye (id, first_name, email, birthday) values (4, 'Octavia', 'oshildrick3@uol.com.br', '12/1/2022');
insert into emplooye (id, first_name, email, birthday) values (5, 'Hewie', 'hpearn4@unesco.org', '7/11/2022');
insert into emplooye (id, first_name, email, birthday) values (6, 'Renata', 'rrubes5@behance.net', '3/25/2023');
insert into emplooye (id, first_name, email, birthday) values (7, 'Sarge', 'sjeakins6@aboutads.info', '3/16/2023');
insert into emplooye (id, first_name, email, birthday) values (8, 'Delila', 'dmakey7@taobao.com', '12/5/2022');
insert into emplooye (id, first_name, email, birthday) values (9, 'Renie', 'rrossander8@msn.com', '1/1/2023');
insert into emplooye (id, first_name, email, birthday) values (10, 'Imelda', 'icurwen9@ustream.tv', '11/17/2022');
insert into emplooye (id, first_name, email, birthday) values (11, 'Horten', 'hskillitta@fotki.com', '3/21/2023');
insert into emplooye (id, first_name, email, birthday) values (12, 'Al', 'akrauzeb@examiner.com', '3/23/2023');
insert into emplooye (id, first_name, email, birthday) values (13, 'Elia', 'esemmensc@technorati.com', '4/11/2023');
insert into emplooye (id, first_name, email, birthday) values (14, 'Sadie', 'sfairhamd@creativecommons.org', '12/29/2022');
insert into emplooye (id, first_name, email, birthday) values (15, 'Sarene', 'sbirtchnelle@yahoo.co.jp', '11/21/2022');
insert into emplooye (id, first_name, email, birthday) values (16, 'Ruggiero', 'rcristobalf@reddit.com', '3/29/2023');
insert into emplooye (id, first_name, email, birthday) values (17, 'Veronique', 'vwodhamg@creativecommons.org', '9/2/2022');
insert into emplooye (id, first_name, email, birthday) values (18, 'Cyndy', 'cpeerth@patch.com', '9/28/2022');
insert into emplooye (id, first_name, email, birthday) values (19, 'Eloisa', 'ehaynei@wired.com', '5/11/2023');
insert into emplooye (id, first_name, email, birthday) values (20, 'Saundra', 'sframej@infoseek.co.jp', '9/13/2022');
insert into emplooye (id, first_name, email, birthday) values (21, 'Kerri', 'kcaunterk@github.io', '8/30/2022');
insert into emplooye (id, first_name, email, birthday) values (22, 'Anne-corinne', 'aaplinl@craigslist.org', '5/29/2023');
insert into emplooye (id, first_name, email, birthday) values (23, 'Euell', 'ekincaidm@nydailynews.com', '12/12/2022');
insert into emplooye (id, first_name, email, birthday) values (24, 'Gaspar', 'ghargroven@bloglovin.com', '11/2/2022');
insert into emplooye (id, first_name, email, birthday) values (25, 'Benedict', 'bjaneso@ifeng.com', '6/25/2022');
insert into emplooye (id, first_name, email, birthday) values (26, 'Brittani', 'bsherrockp@php.net', '9/27/2022');
insert into emplooye (id, first_name, email, birthday) values (27, 'Giselle', 'gtakisq@blog.com', '2/11/2023');
insert into emplooye (id, first_name, email, birthday) values (28, 'Dorry', 'dconyersr@flickr.com', '6/8/2023');
insert into emplooye (id, first_name, email, birthday) values (29, 'Piotr', 'pkarpols@redcross.org', '6/15/2022');
insert into emplooye (id, first_name, email, birthday) values (30, 'Kerry', 'kottont@joomla.org', '4/15/2023');
insert into emplooye (id, first_name, email, birthday) values (31, 'Kris', 'kcholwellu@vimeo.com', '2/10/2023');
insert into emplooye (id, first_name, email, birthday) values (32, 'Westbrooke', 'wrabbv@twitter.com', '12/2/2022');
insert into emplooye (id, first_name, email, birthday) values (33, 'Berty', 'bburgerw@arstechnica.com', '12/25/2022');
insert into emplooye (id, first_name, email, birthday) values (34, 'Henrieta', 'hingleyx@yelp.com', '12/9/2022');
insert into emplooye (id, first_name, email, birthday) values (35, 'Bartolemo', 'bbenedicky@amazon.com', '4/27/2023');
insert into emplooye (id, first_name, email, birthday) values (36, 'Aurea', 'achilversz@google.ru', '9/9/2022');
insert into emplooye (id, first_name, email, birthday) values (37, 'Casper', 'cpaulmann10@irs.gov', '12/27/2022');
insert into emplooye (id, first_name, email, birthday) values (38, 'Meyer', 'mbraywood11@ocn.ne.jp', '1/3/2023');
insert into emplooye (id, first_name, email, birthday) values (39, 'Alphard', 'aloach12@canalblog.com', '3/14/2023');
insert into emplooye (id, first_name, email, birthday) values (40, 'Iris', 'iricket13@ihg.com', '2/2/2023');
insert into emplooye (id, first_name, email, birthday) values (41, 'Reyna', 'rburberye14@163.com', '5/1/2023');
insert into emplooye (id, first_name, email, birthday) values (42, 'Arlen', 'acockrill15@soup.io', '3/10/2023');
insert into emplooye (id, first_name, email, birthday) values (43, 'Didi', 'dquilliam16@hostgator.com', '11/18/2022');
insert into emplooye (id, first_name, email, birthday) values (44, 'Mead', 'mcaser17@goodreads.com', '5/13/2023');
insert into emplooye (id, first_name, email, birthday) values (45, 'Gilda', 'gcrackel18@samsung.com', '1/31/2023');
insert into emplooye (id, first_name, email, birthday) values (46, 'Hetty', 'hbeauman19@lulu.com', '1/26/2023');
insert into emplooye (id, first_name, email, birthday) values (47, 'Sapphira', 'sdot1a@cnet.com', '2/5/2023');
insert into emplooye (id, first_name, email, birthday) values (48, 'Roselia', 'rdeaves1b@sphinn.com', '2/20/2023');
insert into emplooye (id, first_name, email, birthday) values (49, 'Nathanil', 'nstrudwick1c@t.co', '3/27/2023');
insert into emplooye (id, first_name, email, birthday) values (50, 'Tailor', 'tbetz1d@usa.gov', '5/1/2023');

```

### Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
```
update emplooye set
first_name = 'Tailor'
where id = 49

update emplooye set
email = 'asdfbhg@gmail.com'
where first_name ='arlen' 

update emplooye set
first_name = 'rick grimes'
where birthday = '1/26/2023'

```

### Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
```
delete from emplooye where first_name = 'sapphira'
delete from emplooye where id = 20
delete from emplooye where email = 'sdot1a@cnet.com'
delete from emplooye where birthday = '5/1/2023'
delete from emplooye where first_name = 'Mead'
```