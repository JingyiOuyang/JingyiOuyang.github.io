---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About me · Jingyi Ouyang</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
      background: #ffffff;
      color: #2d2d2d;
      line-height: 1.7;
      padding: 2rem 1.5rem;
    }

    .page-wrapper {
      max-width: 780px;
      margin: 0 auto;
    }

    .page-header {
      margin-bottom: 2rem;
      border-bottom: 1px solid #eaeef2;
      padding-bottom: 1.2rem;
    }

    .page-header h1 {
      font-size: 2.2rem;
      font-weight: 600;
      letter-spacing: -0.02em;
      color: #1e2b3c;
      margin-bottom: 0.2rem;
    }

    .page-header .subhead {
      font-size: 1.1rem;
      font-weight: 400;
      color: #4a5b6e;
      margin-top: 0.1rem;
    }

    .contact-links {
      margin-top: 0.8rem;
      display: flex;
      flex-wrap: wrap;
      gap: 0.3rem 1.2rem;
      font-size: 0.95rem;
    }

    .contact-links a {
      color: #2970b0;
      text-decoration: none;
      border-bottom: 1px dotted transparent;
      transition: border-color 0.15s;
    }

    .contact-links a:hover {
      border-bottom-color: #2970b0;
    }

    .contact-links i {
      margin-right: 0.3rem;
      opacity: 0.6;
    }

    .content h2 {
      font-size: 1.5rem;
      font-weight: 600;
      color: #1e2b3c;
      margin: 2rem 0 0.8rem 0;
      padding-bottom: 0.2rem;
      border-bottom: 1px solid #eaeef2;
    }

    .content h2:first-of-type {
      margin-top: 0;
    }

    .content h3 {
      font-size: 1.15rem;
      font-weight: 600;
      color: #1e2b3c;
      margin: 1.2rem 0 0.3rem 0;
    }

    .content p {
      margin: 0 0 0.8rem 0;
      color: #3a4a5c;
    }

    .content ul {
      list-style: none;
      padding-left: 0;
      margin: 0.4rem 0 0.8rem 0;
    }

    .content ul li {
      position: relative;
      padding-left: 1.5rem;
      margin-bottom: 0.35rem;
      color: #3a4a5c;
    }

    .content ul li::before {
      content: "▹";
      position: absolute;
      left: 0;
      color: #2970b0;
      font-weight: 600;
    }

    .content .highlight-box {
      background: #f6f9fc;
      border-left: 4px solid #2970b0;
      padding: 0.8rem 1.2rem;
      margin: 1rem 0 1.2rem 0;
      border-radius: 0 6px 6px 0;
    }

    .content .highlight-box.buaa {
      border-left-color: #d4a017;
      background: #fcfaf3;
    }

    .content .highlight-box.buaa strong {
      color: #b38b1e;
    }

    .content .tag-group {
      display: flex;
      flex-wrap: wrap;
      gap: 0.4rem 0.6rem;
      margin: 0.5rem 0 0.2rem 0;
    }

    .content .tag-group .tag {
      background: #eef3f7;
      padding: 0.05rem 0.9rem;
      border-radius: 20px;
      font-size: 0.8rem;
      color: #2d4055;
      font-weight: 500;
      letter-spacing: 0.01em;
      border: 1px solid #e2e9f0;
    }

    .content .meta-date {
      font-size: 0.9rem;
      color: #6c7e92;
      font-weight: 400;
      margin-left: 0.5rem;
    }

    .content .project-item {
      margin-bottom: 1.6rem;
    }

    .content .project-item .proj-title {
      font-weight: 600;
      font-size: 1.08rem;
      color: #1e2b3c;
      display: flex;
      flex-wrap: wrap;
      align-items: baseline;
      justify-content: space-between;
    }

    .content .project-item .proj-title .date {
      font-weight: 400;
      font-size: 0.85rem;
      color: #6c7e92;
    }

    .content .lang-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 0.5rem 1.5rem;
      margin: 0.5rem 0 0.5rem 0;
    }

    .content .lang-grid .lang-item {
      display: flex;
      justify-content: space-between;
      border-bottom: 1px dashed #e2e9f0;
      padding: 0.2rem 0;
      font-size: 0.95rem;
    }

    .content .lang-grid .lang-item .lvl {
      color: #6c7e92;
      font-size: 0.85rem;
    }

    .content .skill-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 0.8rem 1.8rem;
      margin: 0.5rem 0 0.2rem 0;
    }

    .content .skill-grid .skill-cat {
      font-weight: 500;
      color: #1e2b3c;
      margin-bottom: 0.15rem;
    }

    .content .skill-grid .skill-cat span {
      font-weight: 400;
      color: #3a4a5c;
    }

    .content .footnote {
      font-size: 0.9rem;
      color: #6c7e92;
      border-top: 1px solid #eaeef2;
      padding-top: 1.5rem;
      margin-top: 2rem;
      text-align: center;
    }

    .content .footnote a {
      color: #2970b0;
      text-decoration: none;
    }

    .content .footnote a:hover {
      text-decoration: underline;
    }

    @media (max-width: 600px) {
      body { padding: 1.2rem 1rem; }
      .page-header h1 { font-size: 1.8rem; }
      .contact-links { gap: 0.2rem 0.8rem; font-size: 0.85rem; }
      .content .lang-grid { grid-template-columns: 1fr; }
      .content .skill-grid { grid-template-columns: 1fr; gap: 0.3rem; }
      .content .project-item .proj-title { flex-direction: column; align-items: flex-start; }
    }
  </style>
</head>
<body>
<div class="page-wrapper">

  <header class="page-header">
    <h1>Jingyi Ouyang</h1>
    <div class="subhead">B.Sc. Candidate in Artificial Intelligence</div>
    <div class="contact-links">
      <a href="tel:+8617765236769"><i class="fas fa-phone-alt"></i> +86 177 6523 6769</a>
      <a href="mailto:2503865464@qq.com"><i class="fas fa-envelope"></i> 2503865464@qq.com</a>
      <a href="https://jingyiouyang.github.io/" target="_blank"><i class="fas fa-globe"></i> jingyiouyang.github.io</a>
      <a href="https://github.com/jingyiouyang" target="_blank"><i class="fab fa-github"></i> GitHub</a>
    </div>
  </header>

  <div class="content">

    <p>
      I am a Year 1 undergraduate student from the Faculty of Applied Sciences,
      <a href="https://www.mpu.edu.mo" target="_blank">Macao Polytechnic University</a>,
      pursuing a Bachelor of Science in Artificial Intelligence. 
      I will be exchanging to <strong>Beihang University (BUAA)</strong> in Fall 2026 
      — an exciting step that will deepen my exposure to world-class engineering and research.
    </p>

    <h2>Education</h2>

    <div class="highlight-box">
      <strong>Macao Polytechnic University</strong> · 2025 – 2029 (expected)<br>
      <span style="font-weight:500;">B.Sc. in Artificial Intelligence</span><br>
      <span style="color:#3a4a5c;">
        GPA: <strong>3.61</strong> / 4.0 (Rank: <strong>2<sup>nd</sup></strong>)<br>
        <strong>Relevant coursework:</strong> Python Programming, Java, Computer Science Intro,
        Computer Organization, Discrete Mathematics, Calculus, Linear Algebra.
      </span>
    </div>

    <div class="highlight-box buaa">
      <strong><i class="fas fa-plane-departure" style="color:#b38b1e;"></i> Beijing University of Aeronautics and Astronautics (BUAA)</strong> · Fall 2026<br>
      <span style="font-weight:500;">Exchange Student · School of Computer Science</span><br>
      <span style="color:#3a4a5c;">
        Selected for a one-semester exchange program at one of China’s top engineering universities.
        Will focus on <strong>AI, robotics, and computer systems</strong> in an intensive research-oriented environment.
      </span>
    </div>

    <h2>Project Experience</h2>

    <div class="project-item">
      <div class="proj-title">
        <span><i class="fas fa-robot" style="color:#2970b0; margin-right:0.4rem;"></i>Robotic Arm Teleoperation &amp; Posture Control</span>
        <span class="date">Mar 2026 – present</span>
      </div>
      <ul>
        <li>Participated in a ROS-based robotic arm control project with dual modes: direct remote control and IMU-based human posture mapping.</li>
        <li>Responsible for IMU sensor data acquisition interface testing and preliminary preprocessing; validated sensor data stability and accuracy.</li>
        <li>Assisted in mapping remote control commands to arm drive signals, gaining hands-on experience with open-loop control and system integration.</li>
      </ul>
      <div class="tag-group">
        <span class="tag">ROS</span><span class="tag">IMU</span><span class="tag">Real-time Control</span>
        <span class="tag">Data Acquisition</span><span class="tag">C++</span><span class="tag">Python</span>
      </div>
    </div>

    <div class="project-item">
      <div class="proj-title">
        <span><i class="fas fa-brain" style="color:#2970b0; margin-right:0.4rem;"></i>Algorithms &amp; Data Structures Practice</span>
        <span class="date">2025 – present</span>
      </div>
      <ul>
        <li>Systematically practiced algorithms and data structures on LeetCode using C++; independently solved dozens of problems covering linked lists, trees, hash tables, and more.</li>
        <li>Deepened practical understanding of C++ STL (containers, iterators, algorithms), significantly improving logical thinking and debugging skills.</li>
      </ul>
      <div class="tag-group">
        <span class="tag">C++</span><span class="tag">STL</span><span class="tag">Data Structures</span>
        <span class="tag">LeetCode</span><span class="tag">Problem Solving</span>
      </div>
    </div>

    <h2>Skills &amp; Interests</h2>

    <div class="skill-grid">
      <div>
        <div class="skill-cat"><i class="fas fa-code" style="color:#2970b0;"></i> Programming</div>
        <span>Python, Java, C / C++ (STL), Bash</span>
      </div>
      <div>
        <div class="skill-cat"><i class="fas fa-tools" style="color:#2970b0;"></i> Tools</div>
        <span>PyCharm, IntelliJ IDEA, CLion, Git, Linux</span>
      </div>
      <div style="grid-column: 1 / -1;">
        <div class="skill-cat"><i class="fas fa-heart" style="color:#2970b0;"></i> Technical Interests</div>
        <span>Computer Vision, Robotics, Real-time Systems, Algorithms, AI/ML, Embedded Systems</span>
        <div style="margin-top:0.4rem; font-size:0.92rem; color:#3a4a5c;">
          <i class="fas fa-arrow-right" style="color:#2970b0; font-size:0.75rem;"></i>
          Strong self-learner · rigorous logical thinker · adaptable to new challenges
        </div>
      </div>
    </div>

    <h2>Campus &amp; Languages</h2>

    <div style="display:grid; grid-template-columns: 1fr 1fr; gap: 0 1.5rem; margin: 0.4rem 0 0.2rem 0;">
      <div>
        <h3 style="margin-top:0; font-size:1.05rem;"><i class="fas fa-flag" style="color:#2970b0;"></i> Activities</h3>
        <ul style="margin-top:0;">
          <li><strong>Robotics Interest Group</strong> – active member; aiming to compete in <strong>RoboMaster</strong> / <strong>RoboCon</strong>.</li>
          <li>Passionate about hands-on engineering and interdisciplinary collaboration.</li>
        </ul>
      </div>
      <div>
        <h3 style="margin-top:0; font-size:1.05rem;"><i class="fas fa-language" style="color:#2970b0;"></i> Languages</h3>
        <div class="lang-grid" style="grid-template-columns:1fr; gap:0.1rem;">
          <div class="lang-item"><span>Mandarin Chinese</span><span class="lvl">Native</span></div>
          <div class="lang-item"><span>English</span><span class="lvl">Professional proficiency · daily conversation &amp; technical reading</span></div>
        </div>
        <div style="font-size:0.9rem; color:#4a5b6e; margin-top:0.3rem;">
          <i class="fas fa-globe-asia" style="color:#2970b0;"></i> Preparing for the BUAA exchange — enhancing technical communication in both English and Mandarin.
        </div>
      </div>
    </div>

    <div class="footnote">
      <i class="fas fa-arrow-right"></i> Next stop: <strong>BUAA · Fall 2026</strong> &nbsp;|&nbsp;
      <a href="https://jingyiouyang.github.io/" target="_blank">jingyiouyang.github.io</a>
    </div>

  </div>
</div>

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" />
</body>
</html>
