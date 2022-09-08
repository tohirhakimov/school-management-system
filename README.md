# Skuul school management system

>In search of good school management systems written in laravel, I tried so many although most were quite remarkably good they lacked some essential features that I would have loved in a school management system.This made me passionate in building my own school management system. Although it has been difficult, it's actually forming up into a quite useable project.

![schooldash-dahboard-page](https://user-images.githubusercontent.com/63137056/178576517-412251e7-d272-469f-8a98-ec407b599c7a.png)




School is a multi school management system that aims to make school administration and activities a breeze by using the power of the internet and increased connectinity

## Requirements
* Php 8.0 and above
* Composer 
* Since this project is running laravel 9, we suggest checking out the official requirements

## Installation
* Clone the repository by running the following command in your comamand line below (Or you can dowload zip file from github)
```shell
git clone https://github.com/tohirhakimov/school-management-system
 ```
* Head to the project's directory
```shell
cd school-management-system
 ```
* Install composer dependancies
```shell
composer install
```
* Copy .env.example file into .env file and configure based on your environment
```shell
cp .env.example .env
```
* Generate encryption key
```shell
php artisan key:generate
```
* Migrate the database
```shell
php artisan migrate
```
* Seed database 
```shell
        php artisan db:seed
```
