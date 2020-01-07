## Introduction
Laravel Survey is a Laravel PHP package that allows for easy creation of highly configurable web surveys.

## Features
- Allow addition of many surveys.
- Surveys can be open or time limited.
- Surveys can be filled by anonymous users or registered users.
- Surveys can have unlimited number of questions.
- Questions can be reused in more than one survey.
- Questions have types (radio, checkbox, dropdown list).
- Answers can be predefined (chosen) or given by the users.

## Requirements
- PHP 5.6+
- MySQL 5.6+

## Installation & Configuration
- Upload the (**src**) & (**vendor**) folders to a directory in your server.
- Create your database using the (*database.sql*) script.
- Load the (*vendor/autoload.php*) file in your script using either `require` or `require_once` PHP functions.

## Usage
Instantiate the Survey class passing your database connection to it:
```php
// $conn should be instance of PDO or mysqli connection object.
$my_survey = new \Survey\Survey($conn);
```
