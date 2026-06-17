<html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Hemanth Kumar K | Portfolio</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
}

html{
    scroll-behavior:smooth;
}

body{
    background:linear-gradient(-45deg,#0f172a,#1e3a8a,#4338ca,#7c3aed);
    background-size:400% 400%;
    animation:gradientBG 10s ease infinite;
    color:white;
}

@keyframes gradientBG{
    0%{background-position:0% 50%;}
    50%{background-position:100% 50%;}
    100%{background-position:0% 50%;}
}

header{
    text-align:center;
    padding:80px 20px;
    background:rgba(255,255,255,0.1);
    backdrop-filter:blur(10px);
}

header h1{
    font-size:3rem;
    margin-bottom:10px;
}

header p{
    font-size:1.2rem;
}

nav{
    position:sticky;
    top:0;
    background:rgba(0,0,0,0.3);
    backdrop-filter:blur(10px);
    padding:15px;
    text-align:center;
}

nav a{
    color:white;
    text-decoration:none;
    margin:0 15px;
    font-weight:600;
    transition:.3s;
}

nav a:hover{
    color:#38bdf8;
}

section{
    max-width:1000px;
    margin:30px auto;
    padding:30px;
    border-radius:20px;
    box-shadow:0 8px 32px rgba(0,0,0,.2);
    transition:.4s;
}

section:hover{
    transform:translateY(-8px);
}

#about{
    background:linear-gradient(135deg,#2563eb,#60a5fa);
}

#skills{
    background:linear-gradient(135deg,#5007f9,#9a45ea);
}

#projects{
    background:linear-gradient(135deg,#ec4899,#6e6464);
}

#education{
    background:linear-gradient(135deg,#16a34a,#529a6f);
}
#certifications{
    background:linear-gradient(135deg,#f907c0,#3131e8);
}
#contact{
    background:linear-gradient(135deg,#03c0fa,#818cf8);
}

h2{
    margin-bottom:15px;
    border-left:5px solid white;
    padding-left:10px;
}

.skills{
    display:flex;
    flex-wrap:wrap;
    gap:10px;
}

.skill{
    background:white;
    color:#111827;
    padding:10px 15px;
    border-radius:25px;
    font-weight:600;
}

.project{
    background:rgba(255,255,255,.2);
    padding:20px;
    border-radius:15px;
    margin-top:15px;
}

.btn{
    display:inline-block;
    margin-top:15px;
    padding:12px 24px;
    background:white;
    color:#1e3a8a;
    text-decoration:none;
    border-radius:30px;
    font-weight:bold;
    transition:.3s;
}

.btn:hover{
    transform:scale(1.05);
}

footer{
    text-align:center;
    padding:20px;
}

@media(max-width:768px){
    header h1{
        font-size:2rem;
    }

    nav a{
        display:inline-block;
        margin:8px;
    }

    section{
        margin:15px;
    }
}
</style>
</head>

<body>

<header>
    <h1>HEMANTH KUMAR K</h1>
    <p>MCA Graduate | MERN Stack Developer | Software Engineer Aspirant</p>
    <a href="https://www.linkedin.com/in/hemanthkumar-k-7837ba29a" style="color:rgb(244, 240, 240);" target=_blank>linkedin.hemanthkumar-k-7837ba29a</a><br>

    <a href="https://github.com/hemanth3354/" style="color:rgb(244, 240, 240);" target=_blank>hemanth.github.com</a>
</header>
 

<nav>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#education">Education</a>
    <a href="#contact">Contact</a>
</nav>

<section id="about">
    <h2>About Me</h2>
    <p>
       Aspiring software developer with a Master of Computer Applications (MCA) degree and hands-on
training in full stack development. Eager to contribute technical skills and problem-solving abilities
in a dynamic IT environment. Looking for an entry-level role where I can grow as a professional
and add value to innovative projects.
    </p>
</section>

<section id="skills">
    <h2>Skills</h2>
    <div class="skills">
        <div class="skill">HTML</div>
        <div class="skill">CSS</div>
        <div class="skill">JavaScript</div>
         <div class="skill">Python</div>
        <div class="skill">React.js</div>
        <div class="skill">Node.js</div>
        <div class="skill">MongoDB</div>
        <div class="skill">Java</div>
        <div class="skill">MySQL</div>
        <div class="skill">GitHub</div>
        <div class="skill">Linux</div>
        <div class="skill">Data Structures and Algorithms</div>
    </div>
</section>

<section id="projects">
    <h2>Projects</h2>

    <div class="project">
        <h3>Online Voting System</h3>
        <p>
            Developed a Online Voting System is to digitize and simplify the process of conducting elections
through a secure, efficient, and user-friendly web platform. This system is designed to replace the
traditional paper-based voting process with an electronic alternative, reducing human effort, time,
and the possibility of errors or manipulation.
        </p>
    </div>

    <div class="project">
        <h3>Bus Ticket Booking System</h3>
        <p>
            Developed a full-stack Bus Ticket Booking system enabling users to search, ticket reservation booking, enhances user experience and manage bus tickets with real-time seat availability and payment
integration.
        </p>
    </div>

  
</section>

<section id="education">
    <h2>Education</h2>
    <p><strong>Master of Computer Applications [MCA] -                  [2023  -  2025]</strong></p>
     <p>St. Francis College, Bengaluru | CGPA: 7.7</p>
    <br>
    <p><strong>Bachelor of Computer Applications [BCA] - [2020 - 2023]</strong></p>
    <p> Govt. First Grade College, Kolar | CGPA: 8.3</p>
</section>

<section id="certifications">
    <h2>Certifications and Training</h2>

   <div class="project">
        <h3>MERN Stack Developer Trainee – Xcel Corp  </h3>
        <p>• Built responsive web applications using React.js and Node.js  </p>
           <p>• Worked with MongoDB for backend data management </p>
• Gained hands-on experience in REST APIs and full-stack workflows 

    
    </div>
       <div class="project">
        <h3>JAVA FULL STACK TRAINING – Arcus Infotech </h3>
        <p>• Completed hands-on training in Core Java, OOPS, JDBC, SQL, HTML, CSS, JavaScript </p> 
         <p>• Developed web applications using Java, Servlets (basics), and MySQL </p> 
          <p>• Worked on frontend–backend integration and CRUD operations </p> 
           <p>• Gained practical exposure to software development lifecycle (SDLC)</p> 

    </div>




       <div class="project">
        <h3>Data Analytics Training (Self-Learning)</h3>
        <p>• Completed a Data Analytics training program through YouTube tutorials, where I learned and practiced Excel, SQL, Python, and Power BI. </p>
           <p>• Gained hands-on experience in data cleaning, data analysis, visualization, dashboard creation, and generating business insights using sample datasets.</p>
    </div>


     <div class="project">
        <h3>SOFTWARE TESSING training at Besant Technologies. </h3>
        <p>• Completed hands-on training in STLC, manual testing, test case design, defect life cycle, Agile methodology, and 
basic selenium concepts. </p> 
      
    </div>
       <div class="project">
        <h3>Machine Learning & Data Analytics Trainee – Infosys Springboard </h3>
        <p>• Learned fundamentals of Machine Learning and Data Analytics  </p> 
         <p>• Worked with Python for basic data analysis and data handling  </p>
         <p>• Performed data cleaning and preprocessing on sample datasets  </p>
          <p>• Created simple data visualizations to understand trends and patterns  </p>
           <p>• Gained exposure to basic ML models and analytical concepts  </p>
        
    </div>
  
</section>

    <section id="certifications">
        <h2>Strengths</h2>

       <div class="project">
        <p>• Quick learner with strong problem-solving ability</p>
        <p>• Good communication and teamwork skills</p>
        <p>• Self-motivated and adaptable to new technologies</p>
        <p>• Positive attitude and willingness to take responsibility</p>
    
        
    </div>
</section>

<section id="contact">
    <h2>Contact</h2>
    <p>Email: hemanthkumar3354@gmail.com</p>
    <p>Phone: +91 8317440936</p>

    <a href="resume.pdf" download class="btn">
        Download Resume
    </a>
</section>

<footer>
    <p>© 2026 Hemanth Kumar K. All Rights Reserved.</p>
</footer>

</body>
</html>
