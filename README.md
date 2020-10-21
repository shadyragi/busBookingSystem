<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## Required Configuration

Laravel 1- Import busBooking.sql into database called busBooking and change username and password to root

2 - authentication credentials:
	email: shady@yahoo.com
	password: 12345678

## About Task:

It's a bus-booking system where you can: 

1 - list all trips stored and view start and end station

2 - Book a seat number from available seates that is not yet reserved

3 - system is desgined for trips that travels into one single direction (north to south) so governates are ordered in the database in terms of their geographic location. the more you go to the south, the higher the id of the governate record in DB

for example( cairo's id = 1, Assiut's id = 4 ,... so far so on)

## API URLS:

 - http://localhost:8000/api?api_token=0KG8a7XvWtYApoK6kZ8ZmDasP5qGiTZ5r103DWVx1KciCc5MIPJlUJgQOyUh

 - http://localhost:8000/api/tripBooking?api_token=0KG8a7XvWtYApoK6kZ8ZmDasP5qGiTZ5r103DWVx1KciCc5MIPJlUJgQOyUh&trip_id=1

 - http://localhost:8000/api/checkAvailableSeats?api_token=0KG8a7XvWtYApoK6kZ8ZmDasP5qGiTZ5r103DWVx1KciCc5MIPJlUJgQOyUh&trip_id=1&start_station_id=1&end_station_id=4

 - localhost:8000/api/addBooking?seat_id=3&start_station_id=1&end_station_id=4&trip_id=1&api_token=0KG8a7XvWtYApoK6kZ8ZmDasP5qGiTZ5r103DWVx1KciCc5MIPJlUJgQOyUh


