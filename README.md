# Sign_up-Form
Used to enter individual information of Name, email and Phone no. to the table

trying to join the developers world. Here is my first projet worked with HTML+5 and Java Script. 


First 
http://getbootstrap.com/   download bootstrap
https://datatables.net/    download the release pakage----Download datatables

Go to Downloads on your PC

Open Bootstrap 3,3 7 Folder.....extract all files
open DataTables1.10.15.....Media Files extract js,images,css
and save it on Bootstrap folder

Change the name of the folder to datatables.

add 1 index.html file  and Open it
go to getbootstrap.com ...click Getting started...and click Basic template copy and paste it 

add  	<link href="css/bootstrap.min.css" rel="stylesheet">
	<link href="css/datatables.bootstrap.min.css" rel="stylesheet">
	<script src="js/jquery.js"></script>
    	<script src="js/bootstrap.min.js"></script>
    	<script src="js/jquery.datatables.min.js"></script>
    	<script src="js/datatables.bootstrap.min.js"></script>

on the body 
	
	<div class="container">
	<h1>DataTables</h1>
	</div>
	
go to getbootstrap.com
click css--
define <table>

<table id="data_table" class="table table-striped table-bordered table-hover">
	<thead>
	<tr>
	define the form of the tables(u can copy it from getbootstrap.com)
	
				<form class="form-inline">
				<div class="form-group">
				<label class="sr-only" for="FullName"></label>
				<input type="text" class="form-control" id="FullName" placeholder="Full name">
	
	</tr>
Give id for each rows

<tr id="row1">
<td id="name_row1">George Clooney</td>
<td id="country_row1">george.clooney@hollywood.com</td>
<td id="age_row1">0405678471</td>

<td>
<input type="button" id="edit_button1" value="Edit" class="edit" onclick="edit_row('1')">
<input type="button" id="save_button1" value="Save" class="save" onclick="save_row('1')">
<input type="button" value="Delete" class="delete" onclick="delete_row('1')">
</td></tr>
	</thead>
	<tfoot>
	
	</tfoot>

</table>

........To work with Reat 
Go to Run and install npm globally first
npm install -g create-react-app

Run again and type
create-react-app then type the name of your folder (eg. my_app)
it will be create-react-app my_app

Go to node.js command prompt
type cd my_app
install on my_app folder
type npm install react
     npm install react-bootstrap-table

After finalizing your HTML,Js and SCC

save your html in my_app--->on public forlder
inside my_app folder open src and save on app.js and app.scc

Finally go to node.js command prompt and type 
npm start 

Holaaaaaaa You can see what you did from your web. 

