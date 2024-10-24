<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Profile - Madras Institute of Technology</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <!-- Header Section -->
  <header>
    <div class="container">
      <div class="logo-section">
        <img src="https://static.wixstatic.com/shapes/863723_21273d2c388b43e0b077a1f87eff5385.svg" alt="Logo" class="logo">
        <span class="logo-text">Madras Institute of Technology</span>
      </div>
      <nav>
        <ul class="nav-links">
          <li><a href="#profile">Profile</a></li>
          <li><a href="#education">Education</a></li>
          <li><a href="#skills">Skills</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="hero">
    <div class="hero-content">
      <div class="hero-text">
        <h1>Welcome to My Profile</h1>
        <h1>V Ganesh<h1>
        <p>A Computer Engineering Student from Madras Institute of Technology</p>
      </div>
      <div class="hero-image">
        <img src="https://i.ibb.co/9TNBj4H/cozy-anime-picture-boy-sat-his-desk-night-studying-while-there-are-stars-outside-27550-4823.jpg" alt="Study Image">
      </div>
    </div>
  </section>

  <!-- Profile Section -->
  <section id="profile">
    <div class="container">
      <h2>Profile</h2>
      <p>Hello! I'm a passionate computer engineering student at Madras Institute of Technology, with a keen interest in software development, artificial intelligence, and data structures. My goal is to innovate solutions that can solve real-world problems using technology.</p>
      <p>In addition to my academic pursuits, I enjoy working on personal projects that sharpen my programming skills, and I actively participate in coding competitions to challenge myself and grow as a developer.</p>
    </div>
  </section>

  <!-- Education Section -->
  <section id="education">
    <div class="container">
      <h2>Education</h2>
      <p>Bachelor of Engineering in Computer Engineering
Madras Institute of Technology, Chennai
August 2023 – Present

As a dedicated student of Computer Engineering at the Madras Institute of Technology, I have developed a solid foundation in computer science principles, including algorithms, data structures, and operating systems. I have gained hands-on experience with software development, database management, and embedded systems. My coursework has also covered advanced topics such as artificial intelligence, machine learning, and network security. Actively participating in various coding competitions and hackathons, I am passionate about problem-solving and continuously enhancing my programming skills. Expected graduation: May 2027</p>
    </div>
  </section>

  <section id="skills">
    <div class="container">
      <h2>Skills</h2>
      <p>As a Computer Engineering student, I have developed a diverse set of technical skills that span both software and hardware domains. Proficient in programming languages such as C, C++, Python, and Java, I am skilled in building efficient algorithms and data structures. I have hands-on experience in web development, including HTML, CSS, and JavaScript, along with knowledge of frameworks like React. Additionally, I am familiar with database management systems such as MySQL and MongoDB. In the realm of hardware, I have experience in microcontroller programming, embedded systems, and circuit design. I am also well-versed in version control using Git, and possess strong analytical skills in debugging and problem-solving. My continuous learning approach allows me to quickly adapt to new technologies and challenges.</p>
    </div>
  </section>

  <section id="contact">
    <div class="container">
      <h2>Contact</h2>
      <p>Email: ganeshkamalesh9279@gmal.com</p>
      <p>Follow me on Instagram: <a href="https://www.instagram.com/ganesh_official_308/" target="_blank">Instagram</a></p>
      <p>For more details,view profile in Linkedln: <a href="https://www.linkedin.com/in/ganesh-v-1240632ba/" target="_blank">Linkedin</a></p>

    </div>
  </section>
  <div class="chat-container">
    <div class="chat-box" id="chat-box">
        <div class="bot-message">Hello! I'm your personal chatbot. What would you like to know about me?</div>
    </div>
    <input type="text" id="user-input" placeholder="Type your question..." autofocus>
    <button onclick="processInput()">Send</button>
</div>
<script src="script.js"></script>
</body>
</html>
