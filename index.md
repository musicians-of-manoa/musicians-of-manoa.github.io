<div class="container">
  <h1 id="project-campus-jam">Project: Campus Jam</h1>

  <h2>Table of Contents</h2>
  <ul>
    <li><a href="#overview">Overview</a></li>
    <li><a href="#team">Development Team</a></li>
    <li><a href="#approach">Approach</a></li>
    <li><a href="#guide">Website Guide</a></li>
    <li><a href="#dev-guide">Developer Guide</a></li>
    <li><a href="#history">Development History</a></li>
    <li><a href="#enhancements">Possible Enhancements</a></li>
  </ul>

  <h2 id="overview">Overview<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#overview" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h2>

  <p><em>The problem:</em> Many UH students have musical talents, but there is no easy way for them to find others with similar tastes and compatible musical abilities. Thus, they cannot experience the fun of informal jam sessions which could progress into performing musical groups.</p>

  <p><em>The solution:</em>  The Campus Jam application allows students to login and create a profile indicating their musical tastes, their musical capabilities, and their musical goals (from occasional, informal jam sessions to performing bands). The profile can also include links to YouTube videos or SoundCloud tracks with examples of their musicianship.</p>

  <h2 id="team">Development Team<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#team" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h2>

  <b>
  Dominic Deuz <br>
  Josh Hicks <br>
  Christian Iha <br>
  Dahyun Kwon <br>
  Samantha Limon <br>
  </b>
  <hr>

  <a href="/img/Musicians%20of%20Manoa%20-%20Team%Contract.pdf"><b>Team Contract</b></a>
  <br>
  <a href="/img/Musicians%20of%20Manoa%20-%20Team%20Bonding.pdf"><b>Team Bonding</b></a>

  <h2 id="approach">Approach<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#approach" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h2>

  <p>Once a profile is created, others can browse the profiles filtered by specific tastes, capabilities, and goals to find compatible musicians to contact.</p>

  <p>Students can also set up notifications to find out automatically when a profile is created that satisfies criteria that they specify.</p>

  <p>Admins can monitor the site for inappropriate content, and create new categories of musical tastes, capabilities, and goals.</p>

  <p>Note: if you choose this idea for your final project, you cannot name it “Campus Jam”.  Come up with a different name for your final project.</p>

  <h2 id="guide">Website Guide<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#guide" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h2>

  <p>This section provides a walkthrough of the Musicians of Manoa current interface and its capabilities. Currently, the website is primarily composed of mockup pages, including the following.</p>

  <h3>Landing Page</h3>
  <p>The landing page is presented to users when they visit the top-level URL to the site. This page presents basic information about the project and buttons that will take them to other commonly used pages.</p>
  <div style="display: flex; justify-content: space-around;">
    <img src="/img/landing.png" alt="Landing Page">
  </div>

  <h3>Sign In/Sign Up</h3>
  <p>Click on the "Login" button in the upper right corner of the navbar, then select "Sign in" if you already have an account created, if not you can create an account by clicking "Sign up" instead.</p>
  <div style="display: flex; justify-content: space-around;">
    <img src="/img/signin.png" alt="Sign In Page" style="width: 45%;">
    <img src="/img/signup.png" alt="Sign Up Page" style="width: 45%;">
  </div>

  <h3>Jam Creation Page</h3>
  <p>After logging in, there are more links shown in the navbar including "Create a Jam". Hitting this link will take you to the Jam Creation page, where you can fill in information for a musical jam session which will be posted to the website for other musicians to view.</p>
  <div style="display: flex; justify-content: space-around;">
    <img src="/img/landing.png" alt="Landing Page">
  </div>

  <h3>Edit Musical Goals / Tastes / Experience Pages</h3>
  <p>Musical goals, musical tastes, and musical experience levels are all pieces of information acquired from users when creating their account. This allows jam organizers and fellow musicians to find musicians with specific skills and inclinations. For simplicity, the options for each are limited by site administrators and can be edited on this page.</p>
  <div style="display: flex; justify-content: space-around;">
    <div style="display: flex; justify-content: space-around;">
      <img src="/img/editGoal.png" alt="Edit Goals Page" style="width: 30%;">
      <img src="/img/editTaste.png" alt="Edit Tastes Page" style="width: 30%;">
      <img src="/img/editExperience.png" alt="Edit Experience Page" style="width: 30%;">
    </div>
  </div>

  <h2 id="dev-guide">Developer Guide<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#dev-guide" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h2>

  <p>This section provides information of interest to Next developers wishing to use this code as a basis for their own development tasks.</p>

  <h3>Installation</h3>
  First, make sure you have <a href="https://nodejs.org/en">Node</a> installed.

  Second, visit the <a href="https://github.com/musicians-of-manoa/musicians-of-manoa">Musicians of Manoa</a> GitHub page, and click the "Use this template" button to create your own repository initialized with a copy of this application. Alternatively, you can download the sources as a zip file or make a fork of the repo. However you do it, download a copy of the repo to your local computer.

  Third, after having installed your local copy of the application, cd into the musicians-of-manoa directory with a command terminal and install libraries with:
  <code>
    $ npm install
  </code>

  Fourth, run the system with: 
  <code>
    $ npm run dev
  </code>

  If everything was successful, you will be able to view the application at <a href="http://localhost:3000">http://localhost:3000</a>

  <h2 id="history">Development History<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#history" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h2>
  <p>The development process for the Musicians of Manoa project conformed to <a href="https://courses.ics.hawaii.edu/ics314f24/morea/project-management/reading-guidelines-idpm.html">Issue Driven Project Management</a> practices. These practices include:</p>

  <ul>
    <li><b>Frequent Meetings:</b> Teams should meet at least twice a week to review progress and update tasks, with face-to-face meetings preferred for better coordination.</li>
    <li><b>Task Decomposition:</b> Work should be divided into small tasks taking approximately 72 hours to complete. Longer tasks must be broken into subtasks.</li>
    <li><b>Task Documentation and Ownership:</b> Each task is documented as a GitHub issue with a single owner responsible for its completion. Collaboration is possible, but accountability remains with the designated owner.</li>
    <li><b>Branch-based Task Execution:</b> Each task is associated with its own branch, named using the issue number ("issue-XX"), to reduce conflicts and ensure clear tracking. Completed branches are merged back into the main branch.</li>
    <li><b>Milestone Organization:</b> Tasks are grouped into milestones spanning 7-10 days, each producing a concrete deliverable. Each GitHub issue is assigned to exactly one milestone.</li>
    <li><b>Active Issues Per Member:</b> Each team member should have at least two active issues in the current milestone to ensure steady progress and task availability.</li>
    <li><b>Progress Tracking via GitHub Projects:</b> A GitHub Project board with columns for ToDo, In Progress, and Done is created for each milestone to manage tasks visually and systematically.</li>
    <li><b>Effort Estimation:</b> Effort is estimated in hours for each issue, based on task complexity, dependencies, and resources. Estimates are refined as experience grows.</li>
  </ul>

  <p>The following sections document the development history of BowFolios</p>
  <h3>Milestone 1</h3>
  <p>The goal of Milestone 1 was to create as many mockup pages as possible of the necessary pages for our project, the group deciding building the pages using Nextjs from the start to be the easiest approach.<p>
  <p>Milestone 1 was managed using <a href="https://github.com/orgs/musicians-of-manoa/projects/1">Musicians of Manoa Project Board M1</a></p>
  <div style="display: flex; justify-content: space-around;">
    <img src="/img/M1Board.png" alt="M1 Project Board 24 hours before Milestone 1 was due.">
  </div>

  <h2 id="enhancements">Possible Enhancements<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#enhancements" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h2>

  <p>Here are ideas for more advanced features:</p>

  <ul>
    <li>Support the organization of jam sessions. Provide information on scheduled jam sessions, including location, time, musical type, desired capabilities, and organizer contact information.</li>
    <li>Support a network of “who’s played with who”.</li>
    <li>Support reviews of musicians.</li>
  </ul>

</div>
