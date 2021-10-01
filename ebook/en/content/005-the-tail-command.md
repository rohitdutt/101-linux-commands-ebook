<h1>
  	<a href="https://github.com/bobbyiliev/101-linux-commands-ebook/blob/main/ebook/en/content/005-the-tail-command.md">
    	the-tail-command.md
	</a>
</h1>

The tail command prints the last 10 lines by default of a file.
<br>
<br>
ex: 
 <span style="background-color: #C0C0C0; padding: 5px; border-radius: 4px">tail filename.txt</span>
<br>
<br>
Syntax: <span style="background-color: #C0C0C0; padding: 5px; border-radius: 4px">tail [OPTION] [FILENAME]</span>
<br>
<br>
<br>
<h3>
  		Get a specific number of lines :
</h3>
Use the <span style="background-color: #C0C0C0; padding: 5px; border-radius: 4px">
-n</span> option with a number(should be an integer) of lines to display:
<br>
<br>
ex: 
 <span style="background-color: #C0C0C0; padding: 5px; border-radius: 4px">
tail -n 10 foo.txt</span>
<br>
this command will display the first 10 lines of file foo.txt
<br>
this example will also give same result as above command: 
<br>
 <span style="background-color: #C0C0C0; padding: 5px; border-radius: 4px">tail -10 foo.txt</span>
<br>
<br>
syntax: 
 <span style="background-color: #C0C0C0; padding: 5px; border-radius: 4px">tail -n <~number> foo.txt</span>
