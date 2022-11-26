# README

This is a task-oriented textbook designed for students in secondary and higher education. The emphasis is on creating queries, forms and reports and less on creating new databases. It is therefore also very suitable for anyone who wants to learn to use Access.

The book contains many exercises. There is a database available for teachers with solutions for the exercises.

Required software: Microsoft Access 365, 2016 or 2019. The 2013 and 2010 versions also work well. 

## Practice files

File Practicefiles-LearnAccess.zip contains all files from folder `data` and is generated through the script in `R/generate-zip.R`. When rendering the book, this script is pre-rendered by the option in `_quarto.yml`: pre-render: R/generate-zip.R

The script uses [7-zip](https://www.7-zip.org/) which must be installed on the computer and in the path. The zip file is only updated when an existing file changes or when files are added or removed.

## Interactive content

The interactive parts are answers to questions, tips, solutions, ... These are created by functions in package [webexercises](https://psyteachr.github.io/webexercises/) and this package must be installed.

To use webexercises with Quarto you need to add the `webex.css` and `webex.js` file to the format html option in the `_quarto.yml` file.

To make the functions available in all chapters, the necessary script `webex.R` is executed through R code in file `.Rprofile`. This is the easiest method, otherwise you'll have to include the code at the beginning of each chapter.

## Custom CSS

The css for the webexercises is present in `include/webex.css`.

The css specific for this textbook is in `include/textbook.css`. 

