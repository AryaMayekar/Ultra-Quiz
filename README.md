# Ultra-Quiz

Ultra Quiz is an engaging and interactive platform designed for individuals who enjoy testing their knowledge and competing with others. The platform offers features like time-limited quizzes, leaderboards to track performance, and an instructional panel with rules and regulations to ensure a smooth and fair experience.

<h2>Who is it for?</h2>

<h4>Students, professionals, and knowledge enthusiasts who want to challenge themselves.
Individuals preparing for competitive exams or simply looking to enhance their knowledge.
People who enjoy friendly competition through leaderboards.</h4>

<h2>Purpose:</h2>
<ul>
<li>To provide a structured and enjoyable environment for testing knowledge across various topics.</li>
<li>To encourage learning through gamification by adding elements like rankings.</li>
<li>To inspire users to improve themselves by competing with others in a healthy and motivating manner.</li>
<li>To facilitate quick and engaging quizzes for users with limited time.</li>
</ul>

# Installation Steps:-
<ul>
  <li>Step 1: Install and configure MySQL first, as it is utilized in the backend database, on your device.</li>
  <br>
  <li>Step 2: Now create a database named as mainlogindatabase.</li>
  <br>
  <li>Step 3: Inside the mainlogindatabase database, create a table named users. <br>And run the following query:-
  <br>CREATE TABLE users (
    id INT AUTO_INCREMENT PRIMARY KEY,       -- Unique identifier for each user
    <br>name VARCHAR(255) NOT NULL,              -- Name of the user
    <br>email VARCHAR(255) UNIQUE NOT NULL,      -- Email address (must be unique)
    <br>password VARCHAR(255) NOT NULL,          -- password
    <br>points INT DEFAULT 0                     -- User's points, default is 0
  <br>);
  </li>
  <br>
  <li>Step 5: Now install Python along with Flask,render_template, redirect, url_for,flash, session, make_response,request, jsonify</li>
  <br>
  <li>Step 6: After installing the Libraries, open the app.py file and run the server.
  <br>Press Ctrl and Click on the address provided in the terminal, this will launch the website.</li>
  <br>
  <li>Step 7:After launching website, go to the sign up page and create new accounts. 
  <br>Then use the created accounts to Log in the website. </li>
  <br>
  <li>Step 8:Once logged in u can easily navigate to other pages such as attempting quiz and viewing leaderboard.</li>
</ul>
