<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8"> 
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gym page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
<header>
<div class="container flex">
<div class="brand">
<a href="#">Alt Events</a></div>
<div class="navbar">
<a href="#">Home</a>
<a href="#">About</a>
<a href="#">Service</a>
<a href="#">Contact</a>
<button>Join Us</button>
</div>
</div>


<div class="intro">
<div class="head">
<h1>Web Developer Confrence <em>2020</em></h1>
<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Officiis, commodi. Tenetur officia amet eum fugit quae soluta tempore earum eaque sapiente nostrum provident placeat ullam mollitia.</p>
<button class="btn">Register Now</button></div>


<div class="img">
<img class="hero" src="hero.png"></div>
</div>
</header>

<section>
<div class="about">
<article class="imgart">
<img src="about.png">
</article>
<article class="introart">
<h2>About the Event</h2>
<P>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Consectetur velit voluptatem, numquam odit exercitationem similique neque? </P>
<button class="know" href="#">Know more</button>
</article>
</div>

</section>




<section class="article">
<h3 class="join">Why You Should Join</h3>

<div class="box">
<div class="col1">
<h4>Network</h4>
<P class="p">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Tempora ut dignissimos placeat.</P>
</div>




<div class="col2">
<h4>Great Speakers</h4>
<p class="p">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Corrupti aperiam neque culpa.</p>
</div>

<div class="col3">
<h4>Information</h4>
<p class="p">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Rem quaerat a non?</p>
</div>
</div>
</div>
</section>

<section class="schedule">

    <h6>schedule</h6>

<div class="timing">


<div class="circle">
<p class="datep">06 sept</p></div>

<div class="simg"><img class="image" src="schedule-01.jpg"></div>

<div class="shead"><h5>Digital world Event conversation.</h5>
<p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ad omnis consequuntur, dolore voluptatem quaerat eius maiores.</p></div>

</div>
</div>
</section>


<section class="schedule">
<div class="timing">


<div class="circle">
<p class="datep">07 sept</p></div>

<div class="simg"><img class="image" src="schedule-02.jpg"></div>

<div class="shead"><h5>Web designing conversation.</h5>
<p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ad omnis consequuntur, dolore voluptatem quaerat eius maiores.</p></div>

</div>
</div>
</section>


<section class="schedule">
<div class="timing">


<div class="circle ">
<p class="datep">08 sept</p></div>

<div class="simg"><img class="image" src="schedule-03.jpg"></div>

<div class="shead"><h5>Web Development conversation.</h5>
<p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ad omnis consequuntur, dolore voluptatem quaerat eius maiores.</p></div>

</div>
</div>
</section>



<section class="schedule">
<div class="timing">


<div class="circle dash ">
<p class="datep">09 sept</p></div>

<div class="simg"><img class="image" src="schedule-04.jpg"></div>

<div class="shead"><h5>Digital marketing conversation.</h5>
<p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ad omnis consequuntur, dolore voluptatem quaerat eius maiores.</p></div>
</div>
</div>
<button class="sbtn">Download schedule</button>
</section>




<section class="perform">

<div class="image-box">

<div>
    <img class="mike"  src="speaker.png">
    <p class="png">Great speaker</p>
</div>


<div>
    <img class="mike"  src="speaker.png">
    <p class="png">Total topic</p>
</div>


<div>
    <img class="mike"  src="participants.png">
    <p class="png">Participant</p>
</div>

<div>
    <img class="mike"  src="sponsor.png">
    <p class="png">Sponsor</p>
</div>
</div>
</section>


</body>
</html>

style.css
/* http://meyerweb.com/eric/tools/css/reset/ 
   v2.0 | 20110126
   License: none (public domain)
*/

html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed, 
figure, figcaption, footer, header, hgroup, 
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
	margin: 0;
	padding: 0;
	border: 0;
	font-size: 100%;
	font: inherit;
	vertical-align: baseline;
}
/* HTML5 display-role reset for older browsers */
article, aside, details, figcaption, figure, 
footer, header, hgroup, menu, nav, section {
	display: block;
}
body {
	line-height: 1;
}
ol, ul {
	list-style: none;
}
blockquote, q {
	quotes: none;
}
blockquote:before, blockquote:after,
q:before, q:after {
	content: '';
	content: none;
}
table {
	border-collapse: collapse;
	border-spacing: 0;
}

/*starts here*/
html{font-size: 16px;}
header{max-width: 1200px;
	background-image:  linear-gradient(rgba(60, 60, 247,0.5), rgba(132, 130, 238,0.5)), url(banner.png)  ;
height: 600px;
margin: 0 auto;
}
@font-face{font-family:"nunito 7pt-regular";
src: url(NunitoSans_7pt-Regular.ttf);
}
body{font-family: "nunito 7pt-regular";}

.container{display: flex;
justify-content: space-between;
padding-top: 20px;
}

.brand,a{font-size: 24px;
text-decoration: none;
color: white;
margin-left: 40px;
font-weight: 700;
}
.navbar,a,button{margin-left: 10px;}
button{margin-right: 20px;
padding: 8px 16px;
border: none;
background-color: red;
color: white;
border-radius: 5px;
}
.intro{display: flex;
	justify-content: space-between;
max-width: 1200px;
color: white;
margin-left: 40px;
}
h1{font-size: 30px;
margin-bottom: 30px;
font-weight: 800;
}
p{font-size: 18px;
	line-height: 1.4;
}
.head{width: 40%;
margin-top: 150px;
}

.btn{
padding: 16px 30px;
color: white;
background-color: red;
margin-left:150px;
margin-top: 10px;
}

em{color: red;
font-size: 30px;
}
.hero{width: 60%;
}
.img{width: 500px;
	height: 600px;
	margin-top: 100px;
}
.about{display: flex;
	max-width: 1000px;
	margin: 0 auto;
	margin-top: 40px;


}


.imgart{width: 50%;
}
.imgart,img{width: 300px;
height: 300px;
}
h2{font-size: 26px;
font-weight: 800;
}

.introart{width: 50%;
	margin-left: 40px;
	margin-top: 80px;
}
.know{padding: 8px 16px;
color: white;
background-color: rgb(223, 63, 63);
font-size: 14px;
margin-top: 14px;
margin-left: 20px;
}


.article{max-width: 1000px;
margin: 0 auto;
height: 250px;
background-color: rgb(206, 230, 252);
margin-top: 20px;
}
.box{display: flex;
margin-top: 40px;
}

.col1,.col2,.col3{width: 30%;
padding: 0px 38px;
margin-top: 30px;
border: 1px dashed red;
margin-right: 20px;
}

h3{font-size: 24px;
font-weight: 800;
text-align: center;
padding-top: 20px;
}


h4{font-size: 22px;
	margin-bottom: 10px;
	margin-top: 20px;}

.p{font-size: 14px;
margin-bottom: 10px;}



.circle{width: 100px;
height: 100px;
background-color: rgb(238, 75, 75);
border-radius: 50%;
position: relative;
}
.datep{text-align: center;
margin-top: 40px;
color: white;
width: 20px;
margin-left: 20px;
position: absolute;
text-align: center;
bottom: 30px;
margin-left: 20px;
}

.timing{max-width: 900px;
	display: flex;
	justify-content: space-evenly;
	margin: 0 auto;


}

.simg,.image{width: 150px;
height: 100px;
margin-left: 30px;

}


h6{text-align: center;
font-size: 30px;
font-weight: 800;
margin-top: 30px;
}
h5{font-size: 22px;
font-weight: 700;
}

.sept{width: 20%;}
.simg{width: 30%;}
.shead{width: 50%;}

.timing{margin-top: 70px;}

.sbtn{padding: 8px 16px;
background-color: red;
color: white;
text-align: center;
margin-left: 660px;
margin-top: 20px;
border-radius: none;
}

.perform{max-width: 1000px;
height: 200px;
background-color: rgb(206,230,252);
margin: 0 auto;
margin-top: 40px;
}

.image-box{display: flex;
justify-content: space-evenly;
padding-top:50px ;
}
.mike{width: 100px;
height: 100px;
}
.png{font-weight: 800;}

@media screen and (max-width:700px)
{header{max-width: 1200px;
	background-image:  linear-gradient(rgba(60, 60, 247,0.5), rgba(132, 130, 238,0.5)), url(banner.png);
height: 18.75rem;
margin: 0 auto;
}

@font-face{font-family:"nunito 7pt-regular";
	src: url(NunitoSans_7pt-Regular.ttf);
	}
	body{font-family: "nunito 7pt-regular";}
	
header{height: 15rem;}
.container{display: flex;
justify-content: space-between;
padding-top: 1.2rem;}


.brand,a{font-size: 1.5rem;
	text-decoration: none;
	color: white;
	margin-left: 2.5rem;
	font-weight: 700;}

.navbar,a,button{margin-left: 0.62rem;}	

button{margin-right: 1rem;
padding: 0.1rem 0.3rem;
border: none;
background-color: red;
color: white;
border-radius: 0.3rem;}	
		
.brand{width: 100%;
text-align: center;
}
.navbar,a{font-size: 0.8rem;}
.navbar{width: 100%;
text-align: center;}
.flex{flex-wrap: wrap;}
.head{margin-top: 4rem;
}

.head{width: 50%;}
.img{width: 50%;}
h1{font-size: 0.7rem;
margin-bottom: 0.5rem;
}
p{font-size: 0.5rem;}
.img,.hero{width:8.5rem ;
height: 9.5rem;
margin-right: 2rem;
margin-bottom: 4rem;
}

.btn{padding: 0.5rem 0.5rem;
}
.imgart,img{width: 4rem;
height: 4rem;
}



}






