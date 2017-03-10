# Extract text from HTML

## Description
Write a program that extracts from given HTML file its title (if available), and its body text without the HTML tags.

_Example input:_

	<html>
	  <head><title>News</title></head>
	  <body><p><a href="http://e-dojo.it">eITdojo
    </a>aims to provide free real-world practical
		training for young people who want to turn into
		skilful QA engineers.</p></body>
	</html>

_Output:_ 

Title: News

Text: eITdojo aims to provide free real-world practical training for young people who want to turn into skilful QA engineers.

