<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Divya Pandey | Portfolio</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
}

body{
background:#000;
color:white;
overflow-x:hidden;
scroll-behavior:smooth;
}

/* NAVBAR */

nav{
position:fixed;
width:100%;
padding:20px 60px;
display:flex;
justify-content:space-between;
align-items:center;
background:rgba(0,0,0,0.5);
backdrop-filter:blur(10px);
z-index:1000;
}

nav h2{
color:#0a84ff;
font-size:28px;
}

nav a{
color:white;
text-decoration:none;
margin-left:20px;
transition:0.3s;
font-size:15px;
}

nav a:hover{
color:#0a84ff;
}

/* HERO */

.hero{
height:100vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
padding:20px;
background:linear-gradient(135deg,#000000,#071a2f,#0a84ff);
}

.hero h1{
font-size:65px;
background:linear-gradient(90deg,#0a84ff,#5ac8fa);
-webkit-background-clip:text;
-webkit-text-fill-color:transparent;
}

.hero p{
margin-top:15px;
font-size:22px;
opacity:0.85;
max-width:700px;
}

.btn{
display:inline-block;
margin-top:30px;
padding:14px 30px;
border-radius:30px;
background:#0a84ff;
color:white;
text-decoration:none;
transition:0.3s;
font-weight:600;
}

.btn:hover{
transform:scale(1.08);
box-shadow:0 0 20px rgba(10,132,255,0.7);
}

/* SECTION */

.section{
padding:100px 10%;
text-align:center;
opacity:0;
transform:translateY(40px);
transition:1s;
}

.section.show{
opacity:1;
transform:translateY(0);
}

.section h1{
font-size:42px;
margin-bottom:40px;
color:#0a84ff;
}

.section p{
line-height:1.8;
font-size:18px;
opacity:0.9;
}

/* CARDS */

.cards{
display:flex;
flex-wrap:wrap;
justify-content:center;
margin-top:30px;
}

.card{
background:rgba(255,255,255,0.06);
backdrop-filter:blur(20px);
padding:25px;
margin:15px;
border-radius:20px;
width:270px;
transition:0.4s;
}

.card:hover{
transform:translateY(-10px) scale(1.05);
box-shadow:0 0 25px rgba(10,132,255,0.7);
}

.card h3{
margin-bottom:10px;
color:#5ac8fa;
}

/* PROJECT */

.project{
background:linear-gradient(135deg,#0a84ff,#5ac8fa);
padding:35px;
border-radius:20px;
margin:20px;
color:white;
transition:0.4s;
}

.project:hover{
transform:scale(1.03);
}

/* CERTIFICATES */

.certificate{
background:rgba(255,255,255,0.05);
padding:25px;
border-left:5px solid #0a84ff;
border-radius:15px;
margin:20px auto;
max-width:700px;
transition:0.4s;
}

.certificate:hover{
transform:translateY(-8px);
box-shadow:0 0 20px rgba(10,132,255,0.6);
}

/* GALLERY */

.gallery{
display:flex;
flex-wrap:wrap;
justify-content:center;
gap:25px;
margin-top:40px;
}

.gallery-item{
width:300px;
background:rgba(255,255,255,0.05);
border-radius:20px;
overflow:hidden;
transition:0.4s;
backdrop-filter:blur(10px);
}

.gallery-item:hover{
transform:translateY(-10px) scale(1.03);
box-shadow:0 0 25px rgba(10,132,255,0.6);
}

.gallery-item img{
width:100%;
height:220px;
object-fit:cover;
display:block;
}

.gallery-item h3{
padding:18px;
color:#5ac8fa;
font-size:20px;
}

.gallery-item p{
padding:0 18px 20px;
font-size:15px;
opacity:0.85;
}

/* FORM */

.contact-form{
display:flex;
flex-direction:column;
align-items:center;
margin-top:40px;
}

.contact-form input,
.contact-form textarea{
width:80%;
max-width:500px;
padding:15px;
margin:10px;
border:none;
border-radius:12px;
background:rgba(255,255,255,0.1);
color:white;
outline:none;
}

.contact-form textarea{
height:140px;
resize:none;
}

.contact-form button{
cursor:pointer;
border:none;
}

/* TYPING EFFECT */

#typing-text{
font-size:28px;
color:#0a84ff;
margin-top:20px;
}

#typing-text::after{
content:"|";
animation:blink 1s infinite;
}

@keyframes blink{
50%{
opacity:0;
}
}

/* FOOTER */

footer{
text-align:center;
padding:40px;
opacity:0.6;
border-top:1px solid rgba(255,255,255,0.1);
}

/* MOBILE */

@media(max-width:768px){

nav{
padding:20px;
flex-direction:column;
}

nav div{
margin-top:10px;
text-align:center;
}

nav a{
display:inline-block;
margin:10px;
}

.hero h1{
font-size:42px;
}

.hero p{
font-size:18px;
}

.section{
padding:80px 6%;
}

.gallery-item{
width:100%;
}

}

</style>
</head>

<body>

<!-- NAVBAR -->

<nav>

<h2>Divya</h2>

<div>
<a href="#home">Home</a>
<a href="#about">About</a>
<a href="#skills">Skills</a>
<a href="#education">Education</a>
<a href="#projects">Projects</a>
<a href="#certificates">Certificates</a>
<a href="#gallery">Gallery</a>
<a href="#contact">Contact</a>
</div>

</nav>

<!-- HERO -->

<section class="hero" id="home">

<h1>Divya Pandey</h1>

<p>
Chemical Engineering Student | Creative Thinker | Future Innovator
</p>

<a href="https://www.linkedin.com/in/divya-pandey-a6a85231b" target="_blank" class="btn">
Visit LinkedIn
</a>

</section>

<!-- ABOUT -->

<section class="section" id="about">

<h1>About Me</h1>

<p>
I am a Chemical Engineering student at MIT AOE, Alandi, passionate about innovation, creativity, and continuous learning. I enjoy exploring new technologies, improving my technical knowledge, and building strong professional skills.
</p>

</section>

<!-- SKILLS -->

<section class="section" id="skills">

<h1>Skills & Proficiencies</h1>

<div class="cards">

<div class="card">
<h3>Technical Skills</h3>
<p>Coding, Designing, MS Office, HTML & CSS</p>
</div>

<div class="card">
<h3>Professional Skills</h3>
<p>Team Management, Leadership, Problem Solving</p>
</div>

<div class="card">
<h3>Soft Skills</h3>
<p>Empathy, Adaptability, Flexibility</p>
</div>

<div class="card">
<h3>Languages</h3>
<p>English, Hindi, Marathi, French, Korean</p>
</div>

</div>

</section>

<!-- EDUCATION -->

<section class="section" id="education">

<h1>Educational Background</h1>

<div class="cards">

<div class="card">
<h3>MIT AOE, Alandi</h3>
<p>Bachelor's in Chemical Engineering</p>
<p>2025 - Present</p>
</div>

<div class="card">
<h3>Shivaji Science College</h3>
<p>12th HSC Board - Science</p>
<p>73%</p>
</div>

<div class="card">
<h3>KBCPS School</h3>
<p>10th CBSE Board</p>
<p>92.6%</p>
</div>

</div>

</section>

<!-- PROJECTS -->

<section class="section" id="projects">

<h1>Projects</h1>

<div class="project">
<h2>Chemical Process Innovation</h2>
<p>
Focused on understanding process optimization and safety management concepts.
</p>
</div>

<div class="project">
<h2>Creative Designing Work</h2>
<p>
Worked on digital designs and presentation layouts.
</p>
</div>

</section>

<!-- ACHIEVEMENTS -->

<section class="section">

<h1>Achievements</h1>

<div class="cards">

<div class="card">
🏅 NSO Gold Medal (2018)
</div>

<div class="card">
📜 NSO Certificates (2016 & 2017)
</div>

<div class="card">
⚡ Participation in Prompt War
</div>

</div>

</section>

<!-- CERTIFICATES -->

<section class="section" id="certificates">

<h1>Certificates</h1>

<div class="certificate">
<h2>3 Days French Course Certificate</h2>
<p>
Completed a beginner-level French language course.
</p>
</div>

<div class="certificate">
<h2>NSO Achievement Certificates</h2>
<p>
Received recognition for science olympiad participation.
</p>
</div>

<div class="certificate">
<h2>Prompt War Participation Certificate</h2>
<p>
Participated in AI and creativity-based prompt competition.
</p>
</div>

</section>

<!-- GALLERY -->

<section class="section" id="gallery">

<h1>Certificates & Participations</h1>

<div class="gallery">

<div class="gallery-item">
<img src="C:\Users\HP\Downloads\WhatsApp Image 2026-05-08 at 12.16.34.jpeg" alt="Certificate">
<h3>IBM skills certificate </h3>
<p>Successfully completed IBM course course.</p>
</div>

<div class="gallery-item">
<img src="C:\Users\HP\Downloads\WhatsApp Image 2026-05-08 at 12.16.18.jpeg" alt="Certificate">
<h3>CISCO PYTHON 1 </h3>
<p>got certificate on completion of cisco python 1 course.</p>
</div>

<div class="gallery-item">
<img src="C:\Users\HP\Downloads\WhatsApp Image 2026-05-08 at 15.16.16.jpeg" alt="Event">
<h3>CISCO PYTHON 2</h3>
<p>got certificate on completion of cisco python 1 course.</p>
</div>

<div class="gallery-item">
<img src="C:\Users\HP\Downloads\WhatsApp Image 2026-05-08 at 15.16.10 (1).jpeg" alt="NIRMAAN">
<h3>NIRMAAN 4.0</h3>
<p>Participated in nirmaan 4.0.</p>
</div>

<div class="gallery-item">
<img src="C:\Users\HP\Downloads\WhatsApp Image 2026-05-08 at 15.19.06 (1).jpeg" alt="NASSCOM">
<h3>Nasscom course completion</h3>
<p>completed nasscom 30-hours digital course.</p>
</div>

</div>

</section>

<!-- VISION -->

<section class="section">

<h1>My Vision</h1>

<h2 id="typing-text"></h2>

</section>

<!-- CONTACT -->

<section class="section" id="contact">

<h1>Contact Me</h1>

<div class="cards">

<div class="card">
📞 +91 7709237642
</div>

<div class="card">
📧 divyapandey7733@gmail.com
</div>

<div class="card">
<a href="https://www.linkedin.com/in/divya-pandey-a6a85231b" target="_blank" style="color:#0a84ff;text-decoration:none;">
LinkedIn Profile
</a>
</div>

</div>

<form class="contact-form">

<input type="text" placeholder="Your Name" required>

<input type="email" placeholder="Your Email" required>

<textarea placeholder="Your Message"></textarea>

<button class="btn">Send Message</button>

</form>

</section>

<!-- FOOTER -->

<footer>
<p>© 2026 Divya Pandey | Premium Portfolio Website</p>
</footer>

<!-- JAVASCRIPT -->

<script>

/* TYPING EFFECT */

const quotes = [

"Dream big, work hard, stay focused.",

"Engineering is creativity powered by knowledge.",

"Growth begins outside your comfort zone.",

"Success comes from consistency and discipline."

];

let i = 0;
let j = 0;
let current = "";
let del = false;

function type(){

current = quotes[i];

document.getElementById("typing-text").innerHTML =
del ? current.substring(0,j--) : current.substring(0,j++);

let speed = del ? 50 : 100;

if(!del && j === current.length){

speed = 2000;
del = true;

}

else if(del && j === 0){

del = false;
i = (i + 1) % quotes.length;

}

setTimeout(type,speed);

}

type();

/* SCROLL ANIMATION */

const sections = document.querySelectorAll('.section');

window.addEventListener('scroll', () => {

sections.forEach(sec => {

const top = sec.getBoundingClientRect().top;

if(top < window.innerHeight - 100){

sec.classList.add('show');

}

});

});

</script>

</body>
</html>
