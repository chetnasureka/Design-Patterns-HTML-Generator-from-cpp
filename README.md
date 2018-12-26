# HTML-Generator
HTML Builder using C++ which makes it easy to render C++ files (with CGI and Apache) and to auto generate HTML pages for .txt files.
------------------------------------------------------------------------------------------------------------------------------
1. ## Library: 
	Contains the Node.h, Node.cpp which declares and defines the various html tags and corresponding functions.
	Steps:
	1. Run StaticLib.sh to create a Static Library libNode which can be linked upon usage.
-----------------------------------------------------------------------------------------------------------------------------	
2. ## Website: 
	Demo Application which demonstrates how the library can be used to provide web frontend to existing C++ Applications. 	 
	Makes use of CGI and Apache Services on Ubuntu.
	Steps:
	1. Run cgiScript.sh to create a Static Library and then cgi files out of cpp files finally start apache and move cgi files to appropriate folder and render it.
	2. On the browser go to http://localhost/cgi-bin/hello.cgi.
	Note:
	The Demo Application is a "Frequency Calculator given a String" takes a string input from the user and then runs C++ code to render output on another Html Page.
------------------------------------------------------------------------------------------------------------------------------
3. ## Parser: 
	A parser written in C++ which auto generates the HTML page for any text document making it easier to navigate. This program has basic intelligence to identify URLs, email addresses, lists, paragraphs and even headings based on the length and format of text programed using different RegEx.
	Steps:
	1. Run the RunScript.sh file to create a Static Library and then generate the executable.
	Notes:
	The input is taken from Input.txt file and the Output.html file is generated, both present in the same folder.
------------------------------------------------------------------------------------------------------------------------------
