# NetFlop
### _Movies, TV Shows reviewing website_

## Initial Setup
- Create a Database with name: 'netflop'
- Import 'netflop.sql' to 'netflop' Database
- Modify 'host', 'user', 'pass' (your mysql access) of $config['database'] in configs/database.php
- IMPORTANT (if you are MAC OS user or you don't setup Xampp (or other virtual servers) in default location or there is no htdocs folder): You have to modify the _DEFAULT_PATH at bootstrap.php line 5 and 6 (str_replace).

## Notice

- Main admin username - password: admin - hung
- Sub admin username - password: admin2 - hung

## Tech

- Backend: PHP
- Frontend: CSS, JS, Bootstrap
- Database: MySQL
- API: https://www.themoviedb.org/

## Credit

- TMDB API v3 PHP Library - wrapper to API version 3 of themoviedb.org by 'pixelead0'
(https://github.com/pixelead0/tmdb_v3-PHP-API-/)

## This project has been being worked by a group of 3
- Me - 'Viet Hung Do' as leader, project backend dev, project integrator
- 'Minh Dat Doan' as project frontend dev
- 'Thanh Dat Tran' as project supporter, tester

### This is our first project so i have to admit that this project is far from optimal ^^
### _Studying and researching purpose only!_
