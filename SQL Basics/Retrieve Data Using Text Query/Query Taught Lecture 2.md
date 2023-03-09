select * from movies where imdb_rating>=6 and imdb_rating between 6 and 8;
select * from movies where industry='hollywood'
order by imdb_rating desc limit 5;
select * from movies where release_year in(2022,2019,2018);
select * from movies where release_year=2022 or release_year=2019 or release_year=2018;
