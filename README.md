# Signup-Form
Used to enter individual information of Name, email and Phone no. to the table

For the HTML part
First go to this websites
http://getbootstrap.com/   download bootstrap
https://datatables.net/    download the release pakage----Download datatables

Go to Downloads on your computer to find the 2 files

Open Bootstrap 3,3 7 Folder.....extract all files
open DataTables1.10.15.....Media Files extract js,images,css
and save it on Bootstrap 3,3 7 folder -> Change the name of the folder to datatables

Second	
Open the datatables folder -> add 1 index.html file  and Open it	
go to getbootstrap.com and click Basic template copy and paste it on index.html

Third
Now we are going to work out on our HTML file
add 
<script type="text/javascript" src="table_edit.js"></script>	
<link href="css/bootstrap.min.css" rel="stylesheet">
<link href="css/datatables.bootstrap.min.css" rel="stylesheet">

at the end of the page before </body> </html> write this codes

<script src="js/jquery.js"></script>
<script src="js/bootstrap.min.js"></script>
<script src="js/jquery.datatables.min.js"></script>
<script src="js/datatables.bootstrap.min.js"></script>

Fourth
on the body of the HTML 
	
<div class="container">
Write the name of the table
</div>
	
go to getbootstrap.com-> click css -> define <table> copy and paste it	

<table id="data_table" class="table table-striped table-bordered table-hover">			
	<thead>											
	<tr>
													
	define the form of the tables(u can copy it from getbootstrap.com)
	This part defines what kind of tables we are going to make,
	what to include(Name, email, phone no etc)
	
example:<form class="form-inline">
	<div class="form-group">
	<label class="sr-only" for="FullName"></label>
	<input type="text" class="form-control" id="FullName" placeholder="Full name">
	</tr>
	
Give id for each rows so that we will use the id in table_edit js latter.
example: 
<tr id="row1">
<td id="name_row1">George Clooney</td>
<td id="email_row1">george.clooney@hollywood.com</td>
<td id="phone_row1">0405678471</td>

Here we design our tables edit,save and delete buttons.
<td>
<input type="button" id="edit_button1" value="Edit" class="edit" onclick="edit_row('1')">
<input type="button" id="save_button1" value="Save" class="save" onclick="save_row('1')">
<input type="button" value="Delete" class="delete" onclick="delete_row('1')">
</td></tr>

</thead>
</table>
</body>
</html>

