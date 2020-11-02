# Code Refactor - Accessibility Standards
On this project I have refactored the original code to make it more accessible. 

## Description

Making a website more accessible means to improve its reading capability by technologies that helps people with disabilities to access the internet, such as video captions, screen readers, and braille keyboards. Following accessibility standards also increases the chances of search engines to include your website on the top of the users search.

## Modifications Provide

* Listed page title before css link to improve HTML structure.
* Page title was only “website”. I have modified it to be the brand “Horiseon”.
* Throughout the original code it was written all with < div >. To comply with the accessibility standards I have modified the < div > tags with HTML semantic elements such as < header >, < nav >, < main >, < figure > , < section >, < aside >, and < footer >. Deleted unnecessary class names with these modifications.
* Clean up unnecessary list tags with the new addition of < nav > tag, created a new class “a” for styling part of the < a > tags.
* As all < sections > had the same property value, one single class has been created to substitute the previous three classes. Same approach was made for < aside >.
* Fixed missing id name for Search Engine Optimization that allows the < nav > link to connect to it. 
* Updated style.css file to be in accordance with the modifications provided on index.html, while also improving organization and comments.

## Application link
[Horiseon](https://mimila-85.github.io/Code-Refactor/)

## Visual Result
![Header](https://github.com/Mimila-85/01-html-git-css-Homework/blob/master/Screenshots/Screenshot_1.PNG)
![Section](https://github.com/Mimila-85/01-html-git-css-Homework/blob/master/Screenshots/Screenshot_2.PNG)
![Footer](https://github.com/Mimila-85/01-html-git-css-Homework/blob/master/Screenshots/Screenshot_3.PNG)

