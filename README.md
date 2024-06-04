SELECT COUNT(*) AS number_of_cities
FROM city
WHERE countrycode = 'USA';

SELECT population, lifeexpectancy
FROM country
WHERE code = 'ARG';

select population AS 'population in ARG'. Lifeexpectancy AS 'life expectancy in ARG* from country where code =
•ARG';

select name AS
->
"cities in Brazil'
country of your choice besides the USA
from city
- where countrycode - 'BRA'
->
order
by name;

SELECT name, population
FROM country
WHERE population > 100000000
ORDER BY population DESC;

SELECT name, lifeexpectancy
FROM country
WHERE lifeexpectancy > 80
ORDER BY lifeexpectancy DESC;
