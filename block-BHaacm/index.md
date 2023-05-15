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
<a href="#">
    <img src="logo.png">
</a></div>



<div class="navbar">
<a href="#">Home</a>
<a href="#">Blog</a>
<a href="#">About</a>
</div>
</div>
</header>
<section class="intro">
<div class="big-box flex">
<div class="article">
<h1>What is lorem ipsum?</h1>
<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Iste officiis facilis, porro molestiae debitis ex placeat sint, reprehenderit sit sequi impedit qui distinctio, itaque eligendi? Provident eius cupiditate ratione veritatis eos eveniet repudiandae repellat sint quod aliquam, rem, vitae deserunt vero earum exercitationem, distinctio id dolores ut maiores inventore ipsam. Facere eum suscipit delectus quae officiis. Magnam aut laboriosam officiis ratione non. Amet suscipit voluptatem ullam, illo placeat odio ut eligendi reprehenderit repellendus minus labore quidem eos animi fugit temporibus?suscipit delectus quae officiis. Magnam aut laboriosam officiis ratione non. Amet suscipit voluptatem 

    <button>Read More</button>
</p>
</div>

<div class="img">
<img class="image" src="01.png" alt="png">
</div>
</div>
</section>



<article class="vlog">
<h2>OUR BLOG</h2>

<div class="big-box">

<div class="col">
<img class="images"  src="02.png">
<h3>Why do we use it?</h3>
<p class="ptext">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Odit eos rem est, quod officia repellendus. Labore, modi eos. Laboriosam, dolorum.</p>
<button class="rem">Read More</button>
</div>


<div class="col">
    <img class="images"  src="03.png">
    <h3>Where does it come from?</h3>
    <p class="ptext">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Odit eos rem est, quod officia repellendus. Labore, modi eos. Laboriosam, dolorum.</p>
    <button class="rem">Read More</button>
    </div>
    
    
    
    <div class="col">
        <img class="images"  src="04.png">
        <h3>Where can i get some?</h3>
        <p class="ptext">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Odit eos rem est, quod officia repellendus. Labore, modi eos. Laboriosam, dolorum.</p>
        <button class="rem">Read More</button>
        </div>
        </div>
</article>

<footer>

<p class="foot">@Altcampus</p>


</footer>
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

header,footer{max-width: 1200px;
	width: 100%;
background-color: rgb(9, 9, 71);
margin: 0 auto;
}

@font-face{font-family:"nunito 7pt-regular";
src: url(NunitoSans_7pt-Regular.ttf);}

body{font-family: "nunito 7pt-regular";}

.container{display: flex;
justify-content: space-between;
padding-top: 20px;}

.brand,a{font-size: 18px;
text-decoration: none;
color: white;
margin-left: 40px;
font-weight: 700;
margin-bottom: 10px;
}
.navbar,a{margin-left: 10px;
margin-top: 10px;
}
.navbar{margin-right: 40px;}

.intro{max-width: 1200px;
height: 500px;
background-color: rgb(216, 233, 248);
margin: 0 auto;
}
.big-box{display: flex;
justify-content: space-evenly;
padding-top: 40px;
}


.article{width: 50%;
margin-left: 80px;
}


h1,p{width: 400px;}

.img{width: 50%;}
.image{width: 500px;
height: 350px;}

h1{font-size: 26px;
margin-bottom: 20px;
font-weight: 700;

}
p{font-size: 13px;
line-height: 1.5;
color: grey;
}
button{padding: 12px  18px;
	background-color: rgb(39, 180, 39);
	color: white;
	display: block;
	border: none;
border-radius: 5px;
margin-top: 20px;}


h2{font-size: 28px;
font-weight: 800;
margin-top: 30px;
margin-bottom: 20px;
text-align: center;
}

.vlog{max-width: 1200px;
margin: 0 auto;}

.big-box{display: flex;
justify-content: space-evenly;}


h3,.ptext{width: 300px;}

.col{width: 25%;}

.images{width: 300px;
height: 200px;}

h3{font-size: 18px;
font-weight: 700;
margin-bottom: 10px;
}
.rem{margin-top: 8px;
padding: 6px 12px;
color: white;
border-radius: 3px;
}
footer{padding: 20px 0px;
margin-top: 30px;
max-width: 1200px;
}

.foot{font-size: 24px;
color: grey;
text-align: center;
}

@media screen and (max-width:768px)
{
.brand{width: 100%;
text-align: center;
}

.navbar{width: 100%;
text-align: center;
margin-left: 50px;
margin-bottom: 20px;
}
.flex{flex-wrap: wrap;}

.article{width: 100%;
height: 300px;
}
.img{width: 100%;

}
.image{margin-top: 20px;
margin-bottom: 20px;
height: 300px;
}

.intro{height: 650px;}







}


















