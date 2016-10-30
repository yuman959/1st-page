# 1st-page
<!DOCTYPE html>
<head>
<style>
header{
  text-align: center;
  background: url("http://envye.com/images/customheader3.jpg");
  }
body {
  text-align: center;
  color: grey;
  background-position: 12px 20px;
  font-family: Tahoma;
  }
  
ul {
  padding: 0px 10px 10px 1px;
  }
li{
  display: inline;
  padding: 0px 10px 10px 1px;
  
  }
a {
  color: orange;
  }
h1{
  margin: 0px;
  font-size: 60px;
  color: gold;
  }
  
article { 
  padding: 20px;
  max-width: 500px;
  margin: 0 auto;
  }
  
@media (max-width: 500px){
  h1{
    font-size:40px;
    margin: 0px;
    }
  li{
    display: block;
    padding: 1px;
    }
  }

  img {
    margin: 20px;
    border: 8px solid gold;
    border-radius: 25px;
    }


</style>

</head>

<body>
<header>
<img src="http://lh3.googleusercontent.com/LDBfrJRqgBs6tYbZaPfHQLKjxG9d8uSMyyJdmUbAD_Dn6M0Vxsv4SZR1DcefVJXQMaGX6H8NcUbDqngvUkE7LYQ=s64-c" alt="xi" height="130" width="130">
<h1>Xi's Blog</h1>
<ul>
<li> <a href="#"> about me</a> </li>
<li> <a href="#">portoflio </a> </li>
<li> <a href="#">contact me </a> </li>
<li> <a href="#">blog </a> </li>
</ul>
</header>

<article>
<h2> about me</h2>
<p> this is a paragraph The Digital Homicides are a Steam group with a goal that seems admirable: to keep poorly-made, sketchy, and downright scammy games off Steam. How they go about achieving that goal, however, is far more murky and controversial.
<button>Tweet This</button>
</article>


<article>
<h2>my experience</h2>
<p> The Digital Homicides are a Steam group with a goal that seems admirable: to keep poorly-made, sketchy, and downright scammy games off Steam. How they go about achieving that goal, however, is far more murky and controversial.
<button>Tweet This</button>
</article>


<article>
<h2> my adventure </h2>
<p>The Digital Homicides are a Steam group with a goal that seems admirable: to keep poorly-made, sketchy, and downright scammy games off Steam. How they go about achieving that goal, however, is far more murky and controversial.
<button>Tweet This</button>
</article>

<script>
$("article").on("mouseover",function(){alert("cute girl")});
</script>

</body>
