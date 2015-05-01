<style>
.table {width:80%;margin:1em 5% 3em 10%;}
.tr {width:100%;display:table-row;}
.tr:hover {background-color:#EEE8AA; /* #FF69B4 Hot Pink - Thanks Paul */}
.th {
max-width:300px; /* This is a hack */
width:33%;
text-align:center;
display:table-cell;
border:solid black 1px;
overflow:auto;
font-weight:bold;
background-color:#aaddaa;
}
.td {
max-width:300px; /* This is a hack */
width:33%;
text-align:left;
display:table-cell;
border:solid black 1px;
overflow:auto;
padding:0.25em;
}
.td:hover {background-color:#FFD700; /* Gold */}

@media only screen and (min-width:321px) and (max-width:600px) {
.table {width:90%; margin:1em 2% 3em 5%;}
.th {min-width:150px;font-size:medium;} /* This is a hack */
.td {min-width:150px;font-size:medium;} /* This is a hack */
}

@media only screen and (max-width:320px) {
.table {width:90%; margin:1em 2% 3em 5%;}
.tr {display:inline-block;}
.th {display:table-cell;min-width:120px;font-size:small;}
.td {display:table-cell;min-width:120px;font-size:small;}
}

</style>
# Phonegap-Splashscreen-Test
A simple test of Phonegaps's Splash Screen API.

[table]
! Implemented Platforms
Android
iOS
<div class=table>
	<div class=tr>
		<div class="th"> Implemented Platforms </div>
	</div>
	<div class=tr>
		<div class="td"> Android </div>
	</div>
	<div class=tr>
		<div class="td"> iOS </div>
	</div>
</div>
<div class=table>
	<div class=tr>
		<div class="th"> Supported Platforms </div><div class="th"> Yes (X), No (-) or Quirk (Q) </div>
	</div>
	<div class=tr>
		<div class="td"> Amazon Fire OS </div><div class="td"> X </div>
	</div>
	<div class=tr>
		<div class="td"> Android </div><div class="td"> X </div>
	</div>
	<div class=tr>
		<div class="td"> BlackBerry 10 </div><div class="td"> Q </div>
	</div>
	<div class=tr>
		<div class="td"> iOS </div><div class="td"> Q </div>
	</div>
	<div class=tr>
		<div class="td"> Windows Phone 7 and 8 </div><div class="td"> X </div>
	</div>
	<div class=tr>
		<div class="td"> Windows 8 </div><div class="td"> X </div>
	</div>
</div>

#### CLI and API ####
From: http://docs.phonegap.com/en/3.3.0/cordova_splashscreen_splashscreen.md.html#Splashscreen

#### config.xml ####
From: https://github.com/phonegap/phonegap-start/blob/master/www/config.xml

### Known Issues ###
Phonegap calls these "Quirks".

<div class=table>
	<div class=tr>
		<div class="th"> Supported Platforms </div><div class="th"> Quirk </div>
	</div>
	<div class=tr>
		<div class="td"> BlackBerry 10 </div><div class="td"> The config.xml file's AutoHideSplashScreen setting must be false. </div>
	</div>
	<div class=tr>
		<div class="td"> iOS </div><div class="td"> The config.xml file's AutoHideSplashScreen setting must be false. To delay hiding the splash screen for two seconds, add a timer such as the following in the deviceready event handler: </div>
	</div>
</div>
