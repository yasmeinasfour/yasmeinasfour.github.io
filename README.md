<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <script src="https://cdnjs.cloudflare.com/ajax/libs/aos/2.3.4/aos.js"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/aos/2.3.4/aos.css" />
  <style>
    * {
      transition: all 0.3s ease-in-out;
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

   body {
      font-family: monospace, sans-serif;
    }

   /* Project image hover effects */
    .project-img {
      transition: transform 0.3s ease;
      border-radius: 10px;
    }
    .project-img:hover {
      transform: scale(1.05);
    }

   /* Navigation button effects */
    .nav-button {
      transition: transform 0.2s ease, background-color 0.3s ease;
      padding: 10px 20px;
      text-decoration: none;
      border-radius: 5px;
      color: white;
    }
    .nav-button:hover {
      transform: translateY(-2px);
      filter: brightness(110%);
    }

   /* Profile image animation */
    @keyframes float {
      0% { transform: translateY(0px); }
      50% { transform: translateY(-10px); }
      100% { transform: translateY(0px); }
    }
    .profile-img {
      animation: float 6s ease-in-out infinite;
    }

   /* Experience card effects */
    .experience-card {
      transition: transform 0.3s ease, box-shadow 0.3s ease;
      background: white;
      border-radius: 10px;
      overflow: hidden;
    }
    .experience-card:hover {
      transform: translateX(10px);
      box-shadow: 0 4px 20px rgba(110, 84, 148, 0.15);
    }
    /* Image scroll container */
    .scroll-container {
      height: 300px;
      overflow-y: scroll;
      border: 1px solid #6E5494;
      border-radius: 5px;
      padding: 10px;
      margin-bottom: 10px;
    }
    .scroll-container img {
      width: 100%;
      margin-bottom: 10px;
    }
    /* Custom scrollbar */
    ::-webkit-scrollbar {
      width: 8px;
    }
    ::-webkit-scrollbar-track {
      background: #F3E9FF;
    }
    ::-webkit-scrollbar-thumb {
      background: #8B82F7;
      border-radius: 4px;
    }
    ::-webkit-scrollbar-thumb:hover {
      background: #6E5494;
    }
    /* Responsive grid */
    @media (max-width: 768px) {
      .experience-grid {
        flex-direction: column;
      }
      .project-grid {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>
<body>
  <!-- Header Section -->
  <div style="color: #6E5494; text-align: center; margin: 20px 0;" data-aos="fade-down">
    <h1 style="font-size: 36px; font-weight: bold; margin-bottom: 10px;">Yasmein Asfour</h1>
  </div>

  <!-- Typing Animation -->
  <p align="center" data-aos="fade-up" data-aos-delay="200">
    <a href="https://git.io/typing-svg">
      <img src="https://readme-typing-svg.demolab.com?font=&weight=500&duration=2000&pause=250&color=8B82F7&center=true&vCenter=true&multiline=true&repeat=false&width=800&height=100&lines=+Hi+there!+I'm+Yasmein+Asfour;+an+Electrical+Engineering+major+with+a+minor+in+Computer+Science;Check+out+my+projects+and+experience+below!" 
           alt="Typing SVG" />
    </a>
  </p>

  <p align="center" data-aos="zoom-in" data-aos-delay="400">
    <img src="laptopgif.gif" width="200" class="profile-img"/>
  </p>

  <!-- Navigation -->
  <div style="background-color: #C9D2FD; padding: 20px; border-radius: 10px; margin: 20px;" data-aos="fade-up">
    <div style="display: flex; justify-content: center; gap: 10px;">
      <a href="#projects" class="nav-button" style="background-color: #8B82F7;">Projects</a>
      <a href="#experience" class="nav-button" style="background-color: #D3C4FF;">Experience</a>
      <a href="#skills" class="nav-button" style="background-color: #AA9CED;">Hobbies</a>
    </div>
  </div>

  <!-- About Section -->
  <div style="background-color: #F3E9FF; padding: 20px; border-radius: 10px; margin: 20px;" data-aos="fade-right">
    <h2 style="font-size: 28px; color: #6E5494;">About me</h2>
    <div style="display: flex; align-items: center; flex-wrap: wrap;">
      <p style="font-size: 16px; color: #6E5494; flex: 1; min-width: 300px;">
        Yasmein Asfour is a sophomore from Chicago, Illinois. She is Palestinian-American and pursuing a major in Computer Engineering. She is interested in joining organizations such as the Society of Women Engineers, Engineers Without Borders, Institute of Electrical and Electronic Engineering, and the Muslim Student Association. Having traveled and lived abroad for several years, Yasmein looks forward to participating in the Study Abroad program in either Korea or London. She is enthusiastic about living in DC and hopes to learn more about the historical significance it holds.
      </p>
      <img src="profesh.jpeg" width="200" style="border: 5px solid #C8B8F2; border-radius: 15px; margin-left: 20px;" class="profile-img" />
    </div>
  </div>

  <!-- Projects Section -->
  <div id="projects" style="background-color: #8B82F7; padding: 20px; border-radius: 10px; margin: 20px;" data-aos="fade-up">
    <h2 style="font-size: 28px; color: white; text-align: center;">My Projects</h2>
    <div class="project-grid" style="display: flex; justify-content: center; gap: 20px;">
      <!-- iPod Docking Station -->
      <div style="text-align: center;" data-aos="fade-right" data-aos-delay="200">
        <a href="https://youtube.com/shorts/sxVqf03esyg?feature=share" target="_blank">
          <img src="ipoddockingstation.jpg" width="200" class="project-img" />
        </a>
        <p><a href="https://docs.google.com/document/d/1XPVfb4n8_hlz0ms9uymJM3RGUcBjYHxe/edit" target="_blank" style="color: white; text-decoration: none;">iPod Docking Station Documentation</a></p>
      </div>

      <!-- 8-bit Shift Register -->
   <div style="text-align: center;" data-aos="fade-up" data-aos-delay="400">
        <a href="https://youtu.be/f9jQME5JrBg" target="_blank">
          <img src="8bitshiftregister.jpg" width="200" class="project-img" />
        </a>
        <p><a href="https://docs.google.com/document/d/1jbeXDu222RakOfukz-txorC6X8JEGipzEZ5wkPgFPtM/edit" target="_blank" style="color: white; text-decoration: none;">8-bit Shift Register Documentation</a></p>
      </div>

      <!-- SRAD Flight Computer -->
   <div style="text-align: center;" data-aos="fade-left" data-aos-delay="600">
        <a href="#" target="_blank">
          <img src="flightcomputer.jpg" width="200" class="project-img" />
        </a>
        <p><a href="https://docs.google.com/document/d/1NXahZG1kMCwJgoy31Wl9p9HfCBf4LhcvIHkZc0R1yKk/edit" target="_blank" style="color: white; text-decoration: none;">SRAD Flight Computer Documentation</a></p>
      </div>
    </div>
  </div>

  <!-- Experience Section -->
  <div id="experience" style="background-color: #D3C4FF; padding: 20px; border-radius: 10px; margin: 20px;" data-aos="fade-up">
    <h2 style="font-size: 28px; color: #6E5494; text-align: center;">Professional Experience</h2>
    <div class="experience-grid" style="display: flex; justify-content: space-between; gap: 20px; flex-wrap: wrap;">
      
      <!-- Zain Group -->
   <div class="experience-card" style="text-align: center; flex: 1; min-width: 300px;" data-aos="fade-right" data-aos-delay="200">
        <h3>
          <strong>
            <a href="https://zain.com/en" target="_blank" style="color: #6E5494; text-decoration: none;">
              Data Science & AI Intern (Zain Group)
            </a>
          </strong>
        </h3>
        <p>Jul 2024 - Aug 2024</p>
        <div class="scroll-container">
          <img src="zainlogo.jpeg" alt="Zain Logo" />
          <img src="workingatzain.jpeg" alt="Working at Zain" />
          <img src="dashboardzain.jpeg" alt="Dashboard at Zain" />
        </div>
        <ul style="font-size: 16px; color: #6E5494; text-align: left; margin: 0 auto; max-width: 90%;">
          <li>Utilized Python, Tableau, and APIs to clean, organize, and visually present large datasets.</li>
          <li>Built a churn prediction model using machine learning techniques.</li>
          <li>Presented weekly data analysis findings to the marketing team.</li>
        </ul>
      </div>

      <!-- Sitech -->
   <div class="experience-card" style="text-align: center; flex: 1; min-width: 300px;" data-aos="fade-up" data-aos-delay="400">
        <h3>
          <strong>
            <a href="https://www.sitech.me/" target="_blank" style="color: #6E5494; text-decoration: none;">
              Python Intern (Sitech)
            </a>
          </strong>
        </h3>
        <p>Jul 2023 - Oct 2023</p>
        <div class="scroll-container">
          <img src="sitechoffice.jpeg" alt="Workspace at Sitech" />
          <img src="collegecook.jpeg" alt="The College Cook App" />
        </div>
        <ul style="font-size: 16px; color: #6E5494; text-align: left; margin: 0 auto; max-width: 90%;">
          <li>Led frontend development for "The College Cook" web app using JavaScript, HTML5, and CSS3.</li>
          <li>Collaborated on backend development using Python and Django.</li>
          <li>Encouraged collaborative coding among teammates for efficient project completion.</li>
        </ul>
      </div>

      <!-- Omrania -->
   <div class="experience-card" style="text-align: center; flex: 1; min-width: 300px;" data-aos="fade-left" data-aos-delay="600">
        <h3>
          <strong>
            <a href="https://omrania.com/" target="_blank" style="color: #6E5494; text-decoration: none;">
              Engineering Intern (Omrania & Associates)
            </a>
          </strong>
        </h3>
        <p>May 2021 - Aug 2021</p>
        <div class="scroll-container">
          <img src="thekafd.jpeg" alt="King Abdullah Financial District" />
          <img src="logoomrania.jpeg" alt="Omrania Logo" />
        </div>
        <ul style="font-size: 16px; color: #6E5494; text-align: left; margin: 0 auto; max-width: 90%;">
          <li>Collaborated with engineers on project planning, design, and implementation.</li>
          <li>Delivered a comprehensive project status presentation for an ongoing initiative.</li>
        </ul>
      </div>
    </div>
  </div>

  <!-- Skills/Hobbies Section -->
  <div id="skills" style="background-color: #AA9CED; padding: 20px; border-radius: 10px; margin: 20px;" data-aos="fade-up">
    <h2 style="font-size: 28px; color: #6E5494; text-align: center;">🛠 Hobbies</h2>
    <p style="font-size: 16px; color: #6E5494; margin-bottom: 20px;" data-aos="fade-up" data-aos-delay="200">
      I am a dedicated rocket science enthusiast and currently lead the avionics team for GW Rocket. I am overseeing a project to develop an SRAD flight computer, where I established five specialized teams to handle various aspects of the design and implementation. My role involves creating the project outline, delegating tasks, ensuring progress stays on schedule, and providing technical guidance. I also mentor sophomores and freshmen, teaching them coding concepts, assisting with debugging, and ensuring they have a strong understanding of the work before contributing to the project.
    </p>
    <div style="display: flex; flex-direction: column; gap: 20px; align-items: center;">
      <img src="medoingrecovery.jpeg" data-aos="fade-up" data-aos-delay="400" style="max-width: 100%; border-radius: 10px;"/>
      <img src="myteam.jpeg" data-aos="fade-up" data-aos-delay="600" style="max-width: 100%; border-radius: 10px;"/>
      <img src="spaceportcup.jpeg" data-aos="fade-up" data-aos-delay="800" style="max-width: 100%; border-radius: 10px;"/>
    </div>
  </div>

  <script>
    // Initialize AOS
    document.addEventListener('DOMContentLoaded', function() {
      AOS.init({
        duration: 1000,
        once: true,
        offset: 100
      });
    });
