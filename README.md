
<style>
h1 {text-align: center;}

h2 {text-align: center;}
.aligncenter {
    text-align: center;
}

img {
border: 3px solid #003366;}
div {
	text-align: justify;
 	text-justify: inter-word;}
.float-img{
	float: left;
	clear: right;
	margin-right: 10px;
	margin-bottom: 5px;
	padding: 2px;
}

.footer {position: relative;
   height:100px;
   margin-top:-100px;
   background: AliceBlue;
   color: black;
   text-align: center;
   font-size:20px;
   clear:both;
}

</style>

<body style="background-color:rgba(255, 99, 71, 0.2);">

<h1>Welcome to Joy Teo's First Website!</h1>
<p class="aligncenter"> <b>About Me</b> </p> 
<h2 style="color:DodgerBlue;"> <strong><i>CLICK ME!</i></strong></h2>
<p class="aligncenter"><a href="https://www.linkedin.com/in/joy-teo-43238814a/"><img src="Joy.jpg" width="200" height="250" align="center"/> </a></p>
	
<p class="aligncenter"><b>Academic:</b> Bachelor of Process Engineering; Class of 2021 </p>
<p class="aligncenter">For more information, please visit my <a href="https://www.linkedin.com/in/joy-teo-43238814a/"> LinkedIn!</a> </p>
<p class="aligncenter"> <b>OR </b></p>
<p class="aligncenter"> Download my resume <a href="Resume Online.pdf">here</a></p>
<br>


<a href="https://www.britannica.com/place/Malaysia">
<img src="overview-Malaysia.jpg" width="700" height="450" class="float-img"/></a> 
<p>
<strong>BUT.....let's take it back to where it all started...</strong> <br>
<div>I was born in a beautiful country in Southeast Asia called Malaysia, to an awesome pair of parents named Ronnie and Angela in year 1997! Malaysia is nothing like Newfoundland (weather wise), here it is scorching hot 365 days a year, you would be saving your money on buying a puffer jacket from Winners! Nonetheless, I am grateful to grow up in a country, which consists of many different races (Malay, Chinese, and Indian) that allowed me to be exposed to different cultures and languages at such a young age! </div><br>
<i>*Feel free to click on the landscape of Malaysia to learn more about my home country</i>
<br>
<h1> <strong>High School - SMK Bandar Utama 3 </strong></h1>
<img src="YE.jpeg" width="400" height="350" class="float-img"/> 
<h3> <strong>Young Enterprise (YE) Programme </strong></h3>
<p><div>When I was 16 years of age, I decided to challenge myself into a program called Young Enterprise (YE), where we, as a team of students take our ideas and turn them into business opportunities by running a own company, named Prodigy Enterprise with a funding of approximately 250 CAD. In the team, I was honored to be elected as a Vice President, where I had to lead a team of 50 students in decision making, conducted marketing campaigns on campus to increase brand awareness, and others throughout the whole program. We experienced the full business cycle from capitalization to voluntary liquidation and had to raise capital for our own business through sale of shares. In the end of the 9 months program, we made history by being the team, who earned the highest amount of profit compared to previous teams that have participated in the program and was published in the local newspaper. </div></p>
<br><br><br><br><br><br><br>
<img src="TKD2.png" width="500" height="250" class="float-img"/>
<h3> <strong>Taekwondo </strong></h3>
<div>Throughout my high school, I was also part of the Taekwondo club for 2 years, where I trained and pushed myself to my limits through examinations of acquiring a higher level of belts by performing Taekwondo skills that I have learnt through belt testing. Throughout the 2 years, I managed to achieve a blue belt, which is the third highest in order of colors of belt.</div>
<br><br><br><br><br><br><br><br><br>
<img src="high school.jpg" width="400" height="300" class="float-img"/>
<h3> <strong>End of High School~</strong></h3>
After 5 full years of creating memories, I was able to graduate high school successfully and took my experiences to a higher level. 
<br><br><br><br><br><br><br><br><br><br>
<h2>Take a Quiz before you go!</h2>
<form id="form1">
<p>When is Canada's Birthday?</p>
<label for="var_thirtyone"><input type="radio" name="variable" value="0" id="var_thirtyone" />July 31.</label><br>
<label for="var_first"><input type="radio" name="variable" value="100" id="var_first" />July 1</label><br>
<label for="var_sept"><input type="radio" name="variable" value="0" id="var_sept" />September 1</label><br>
<label for="var_dec"><input type="radio" name="variable" value="0" id="var_dec"/>December 31</label><br>
<button type="submit" value="Submit">Submit</button><br>
</form>
<p>Your grade is: <span id="grade">__</span></p>
<script>
document.getElementById("form1").onsubmit=function() {
      variable = parseInt(document.querySelector('input[name = "variable"]:checked').value);
      
result = variable;
	  
document.getElementById("grade").innerHTML = result;
	
return false; 
}
</script>
<br><br><br>
<hr>
<survey>
<p style="font-size:20px" text-align="left"><b> What do you think of the website: </b></p>
<input type="radio" name="yesorno" value="">Impressed! <br>
<input type="radio" name="yesorno" value="">Good try <br>
<input type="radio" name="yesorno" value="">Bad <br>
Others: <br><textarea rows="5" cols="80"></textarea><br>
<input type = "Submit" name=" Submit" onclick="alert('Not Ready for Criticisms, Thanks for your patience!')">
<p style="font-size:20px"> <b>Any Suggestions: </b></p>
<textarea rows="10" cols="80"></textarea><br>
<input type = "Submit" name=" Submit" onclick="alert('Hold up, still under construction')">
</survey>
<br><br><br><br><br><br><br>
</body>
<div class="footer">
<b>Please contact me for further information!</b><br>
<a href="mailto:jlmteo@mun.ca">jlmteo@mun.ca</a><br>
+1(709)746-8260
