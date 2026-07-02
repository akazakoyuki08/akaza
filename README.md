<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>E-Learning Management System</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
}

body{
background:#0d1117;
color:#fff;
}

header{
height:70px;
background:#161b22;
display:flex;
justify-content:space-between;
align-items:center;
padding:0 40px;
border-bottom:1px solid #30363d;
position:fixed;
width:100%;
top:0;
left:0;
z-index:100;
}

.logo{
font-size:26px;
font-weight:700;
color:#58a6ff;
}

nav a{
color:#c9d1d9;
text-decoration:none;
margin-left:25px;
transition:.3s;
}

nav a:hover{
color:#58a6ff;
}

.container{
display:flex;
margin-top:70px;
}

.sidebar{
width:250px;
background:#161b22;
height:calc(100vh - 70px);
padding:25px;
position:fixed;
left:0;
overflow:auto;
}

.sidebar h3{
margin-bottom:20px;
color:#58a6ff;
}

.sidebar a{
display:block;
padding:12px;
margin:8px 0;
text-decoration:none;
color:#c9d1d9;
border-radius:8px;
transition:.3s;
}

.sidebar a:hover{
background:#21262d;
}

.content{
margin-left:250px;
padding:40px;
width:100%;
}

.hero{
background:#161b22;
padding:40px;
border-radius:15px;
display:flex;
justify-content:space-between;
align-items:center;
flex-wrap:wrap;
}

.hero-text{
max-width:600px;
}

.hero h1{
font-size:40px;
margin-bottom:15px;
}

.hero p{
color:#8b949e;
line-height:1.7;
margin-bottom:20px;
}

button{
padding:12px 30px;
background:#238636;
border:none;
color:white;
font-size:16px;
border-radius:8px;
cursor:pointer;
transition:.3s;
}

button:hover{
background:#2ea043;
}

.hero img{
width:350px;
max-width:100%;
}

.section-title{
margin:40px 0 20px;
font-size:28px;
}

.cards{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
}

.card{
background:#161b22;
border:1px solid #30363d;
border-radius:12px;
overflow:hidden;
transition:.3s;
}

.card:hover{
transform:translateY(-8px);
}

.card img{
width:100%;
height:180px;
object-fit:cover;
}

.card-content{
padding:20px;
}

.card h3{
margin-bottom:10px;
}

.card p{
font-size:14px;
color:#8b949e;
margin-bottom:15px;
}

.progress{
width:100%;
height:8px;
background:#30363d;
border-radius:20px;
overflow:hidden;
margin-bottom:15px;
}

.progress div{
height:100%;
background:#238636;
}

footer{
margin-top:50px;
text-align:center;
padding:25px;
color:#8b949e;
border-top:1px solid #30363d;
}

@media(max-width:900px){

.sidebar{
display:none;
}

.content{
margin-left:0;
}

header{
padding:0 20px;
}

.hero{
text-align:center;
}

.hero img{
margin-top:30px;
}

}

</style>

</head>
<body>

<header>

<div class="logo">
E-Learn
</div>

<nav>
<a href="#">Home</a>
<a href="#">Courses</a>
<a href="#">Dashboard</a>
<a href="#">Certificates</a>
<a href="#">Profile</a>
</nav>

</header>

<div class="container">

<div class="sidebar">

<h3>Dashboard</h3>

<a href="#">🏠 Home</a>
<a href="#">📚 My Courses</a>
<a href="#">🎥 Live Classes</a>
<a href="#">📝 Assignments</a>
<a href="#">📈 Progress</a>
<a href="#">🏆 Certificates</a>
<a href="#">⚙ Settings</a>

</div>

<div class="content">

<div class="hero">

<div class="hero-text">

<h1>Learn New Skills Online</h1>

<p>
Join thousands of students learning programming,
web development, AI, machine learning, design,
and much more.
</p>

<button>Start Learning</button>

</div>

<img src="https://images.unsplash.com/photo-1516321318423-f06f85e504b3?w=600" alt="Learning">

</div>

<h2 class="section-title">
Popular Courses
</h2>

<div class="cards">

<div class="card">

<img src="https://images.unsplash.com/photo-1498050108023-c5249f4df085?w=600">

<div class="card-content">

<h3>HTML & CSS</h3>

<p>Learn complete website design from scratch.</p>

<div class="progress">
<div style="width:70%"></div>
</div>

<button>Continue</button>

</div>

</div>

<div class="card">

<img src="https://images.unsplash.com/photo-1555066931-4365d14bab8c?w=600">

<div class="card-content">

<h3>JavaScript</h3>

<p>Become a JavaScript expert with projects.</p>

<div class="progress">
<div style="width:45%"></div>
</div>

<button>Continue</button>

</div>

</div>

<div class="card">

<img src="https://images.unsplash.com/photo-1515879218367-8466d910aaa4?w=600">

<div class="card-content">

<h3>Python</h3>

<p>Master Python programming from beginner.</p>

<div class="progress">
<div style="width:90%"></div>
</div>

<button>Continue</button>

</div>

</div>

<div class="card">

<img src="https://images.unsplash.com/photo-1517694712202-14dd9538aa97?w=600">

<div class="card-content">

<h3>Artificial Intelligence</h3>

<p>Learn AI and Machine Learning fundamentals.</p>

<div class="progress">
<div style="width:30%"></div>
</div>

<button>Continue</button>

</div>

</div>

</div>

<footer>

© 2026 akazakoyuki||gopi

</footer>

</div>

</div>

</body>
</html>
