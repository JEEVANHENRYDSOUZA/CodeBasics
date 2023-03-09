select title from movies order by release_year desc ;
select title as movie_name from movies where release_year=2022;
select title as movie_name from movies where release_year>=2020;
select title as movie_name from movies where release_year>=2020 and imdb_rating>8;

select title as movie_name from movies where studio='Marvel Studios' or studio='Hombale Films';
select title as movies_name from movies where title like '%Thor%' order by release_year desc;
select title,release_year from movies where not studio='Marvel Studios';
