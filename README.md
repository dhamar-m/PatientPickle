# PatientPickle
html {
	margin:0;
	padding:0;
	background-color:#B7B7CA;
}
h1 {
	font-family:"Open Sans", sans-serif;
	color:#191970;
	text-align:center;
}
h2 {
	font-family:"Open Sans", sans-serif;
	color:#676792;
	text-align:center;
}
body {
	font-family:"Open Sans", sans-serif;
	color:#072436;
	text-align:center;
	
}
p {
	font-family:"Open Sans", sans-serif;
	color:#FF0000;
	text-align:center;
}

.btn {
	font-family:"Open Sans", sans-serif;
	background-color:#503962;
	color:#072436;
}

#button_1{
	background-color:#503962;
	border-color:#503962;
}

#button_2{
	background-color:#503962;
	border-color:#503962;
}

#button_3{
	background-color:#503962;
	border-color:#503962;
}

#it{
	background-color:#B7B7CA;
}

#footer {
   position:fixed;
   left:0px;
   bottom:0px;
   margin-bottom:1%;
   height:30px;
   width:100%;
}

#block1{
	background-color:#F0ECF3;
	margin-left:30%;
	margin-right:30%;
	margin-top:3%;
	border-radius:3%;
}
#block2
h1{
	color:#072435;
	font-size:200%;
	padding-top:5%;
	text-align:center;
}
 hr{
	 border-color:#072435;
	 margin-left:10%;
	 margin-right:10%;
 }
 a{
	 color:#2F6788;
 }
 h4{
	  padding-bottom:5%;
 }
 
 #button1
 .nav{
	 margin-left:30%;
 }

 /*------TO MAKE THE NAV BAR------*/

 /* Remove margins and padding from the list, and add a black background color */
ul.topnav {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
    background-color: #333;
}

/* Float the list items side by side */
ul.topnav li {float: left;}

/* Style the links inside the list items */
ul.topnav li a {
    display: inline-block;
    color: #f2f2f2;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
    transition: 0.3s;
    font-size: 17px;
}

/* Change background color of links on hover */
ul.topnav li a:hover {background-color: #555;}

/* Hide the list item that contains the link that should open and close the topnav on small screens */
ul.topnav li.icon {display: none;}

/* When the screen is less than 680 pixels wide, hide all list items, except for the first one ("Home"). Show the list item that contains the link to open and close the topnav (li.icon) */
@media screen and (max-width:680px) {
  ul.topnav li:not(:first-child) {display: none;}
  ul.topnav li.icon {
    float: right;
    display: inline-block;
  }
}

/* The "responsive" class is added to the topnav with JavaScript when the user clicks on the icon. This class makes the topnav look good on small screens */
@media screen and (max-width:680px) {
  ul.topnav.responsive {position: relative;}
  ul.topnav.responsive li.icon {
    position: absolute;
    right: 0;
    top: 0;
  }
  ul.topnav.responsive li {
    float: none;
    display: inline;
  }
  ul.topnav.responsive li a {
    display: block;
    text-align: left;
  }
}


#myTopnav{
  font-family:"Catamaran", sans-serif, monospace;
}
/*------------NAV BAR CODE ENDS-----------*/


#yourpatients{
  border-style: double;
  border-radius: 20px;
  text-align: center; font-family:"Open Sans", sans-serif, monospace;
  font-size: 40px; color: black;  background-color: rgba(183, 183, 183, .7);
    width: 40%;
    border: 2px solid black;
    padding: 10px;
    margin-left: auto;
    margin-right: auto;
  float:center;
}

#credits{
  border-style: double;
  border-radius: 20px;
  text-align: center; font-family:"Open Sans", sans-serif, monospace;
  font-size: 40px; color: black;  background-color: rgba(183, 183, 183, .7);
    width: 40%;
    border: 2px solid black;
    padding: 10px;
    margin-left: auto;
    margin-right: auto;
  float:center;
}

#genQinstruc{
  border-style: double;
  border-radius: 20px;
  text-align: center; font-family:"Open Sans", sans-serif, monospace;
  font-size: 15px; color: black;  background-color: rgba(183, 183, 183, .7);
    width: 40%;
    border: 2px solid black;
    padding: 10px;
    margin-left: auto;
    margin-right: auto;
  float:center;
}

