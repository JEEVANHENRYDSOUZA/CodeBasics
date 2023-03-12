
select m.title ,l.name   from movies as m inner join languages as l on m.language_id=l.language_id;
select m.title ,l.name   from movies as m inner join languages as l on m.language_id=l.language_id where l.name='Telugu';
  	SELECT 
            l.name, 
            COUNT(m.movie_id) as no_movies
	FROM languages l
	LEFT JOIN movies m USING (language_id)        
	GROUP BY language_id
	ORDER BY no_movies DESC;
