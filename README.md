1. Creating and Renaming Files/Directories
	Create a directory named test_dir using mkdir.
o	mkdir test_dir
 
	Inside test_dir, create an empty file called example.txt.
o	cd mkdir; touch example.txt
 
	Rename example.txt to renamed_example.txt using mv
o	mv example.txt renamed_example.txt
 

2. Viewing File Contents
	Use cat to display the contents of /etc/passwd.
o	cat /etc/passwd
 
	Display only the first 5 lines of /etc/passwd using head.
o	head -n 5 /etc/passwd
 
	Display only the last 5 lines of /etc/passwd using tail.
o	tail -n 5 /etc/passwd
 
3.Searching for Patterns
	Use grep to find all lines containing the word "root" in /etc/passwd.
o	grep root /etc/passwd
 

4. Zipping and Unzipping
	Compress the test_dir directory into a file named test_dir.zip using zip.
o	zip test_dir.zip test_dir
 
	Unzip test_dir.zip into a new directory named unzipped_dir.
o	unzip test_dir.zip
 

5. Downloading Files
	Use wget to download a file from a URL (e.g., https://example.com/sample.txt).
o	wget https://txt2html.sourceforge.net/sample.txt
 

6. Changing Permissions
	Create a file named secure.txt and change its permissions to read-only for everyone using chmod.
o	touch secure.txt
o	chmod 444 secure.txt
 
7. Working with Environment Variables
	Use export to set a new environment variable called MY_VAR with the value "Hello, Linux!".
o	export MY_VAR="Hello Linux!"

Submission Guidelines -: Attach Screenshots or command along with explanation and submit in doc(google doc or microsoft doc) format also attach github repo link

