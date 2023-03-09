select min(imdb_rating) as min_rating,avg(imdb_rating)  as average , round(avg(imdb_rating),2) as round_average from movies;
select min(release_year) as min_release_year , max(release_year) as max_release_year from movies;
select count(*) as released_between from movies where release_year between 2015 and 2022;
 select release_year, count(*) as movies_count 
   from movies group by release_year order by release_year desc;
