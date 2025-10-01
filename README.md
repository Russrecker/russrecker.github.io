# CS 499 Computer Science Capstone

### Professional Self-Assessment
Hi, my name is Russell Reckhow and I am finishing up my bachelor's degree in Computer Science at Southern New Hampshire University. When I started this program, I had little to no background in computer science. Over time I learned new skills and built projects that show I can design, code, and solve problems. Working on the Capstone gave me the chance to see how much I’ve improved since starting the program.

Some of my favorite classes gave me the chance to work on cool projects and see how computer science applies in different ways. In CS-330 Computer Graphics and Visualization, I built a 3D OpenGL scene that showed me how graphics work in programming. In CS-465 Full Stack Development, I worked on the Travlr Getaways project, where I used the MEAN stack and learned how the front-end and back-end work together. In CS-370 Current & Emerging Trends in CS, I built a reinforcement learning pirate agent to find the fastest way to the treasure. These classes gave me hands-on experience and helped me grow my skills in different areas of computer science.

The program also gave me the chance to connect with other classmates through discussions and the unofficial school Discord. I was able to talk with other students, share feedback, and get new ideas, which helped me improve my work. This showed me how important collaboration is, because explaining my thought process and listening to others made me a better problem solver.

The program helped me build skills that I’ll take with me, whether in a computer science career or another path I decide to follow. I learned how to use algorithms and data structures to make my code run better, how to design apps in a way that makes sense for users, and how to work with databases to store and pull data. I also started paying more attention to security, like checking inputs, tying data to specific users, and avoiding mistakes that could cause problems. These are all things I know will carry over into real projects.

Building this ePortfolio shows my growth and the skills I will use in my career. I focused on three areas:
- Software Design and Engineering
- Algorithms and Data Structures
- Databases

Everything came together in my Capstone project, where I went back to the Weight Tracker app I first built in CS-360 and made improvements in these three areas. I added a graph, a merge sort algorithm, and a notes feature, which gave me the chance to put what I learned into practice and show growth across computer science. Working on the Capstone showed how much I’ve improved since I started, and that I can plan, build, and finish projects that actually work.

---

### Code Review Video
<div class="video">
  <iframe
    src="https://www.youtube.com/embed/mLdLV2cGZS4"
    title="Code Review Video"
    loading="lazy"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
    allowfullscreen></iframe>
</div>

<style>
.video { position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; }
.video iframe { position: absolute; top: 0; left: 0; width: 100%; height: 100%; border: 0; }
</style>

In this video, I walked through the original Weight Tracker app, explained the existing functionality, and described the enhancements I planned for design, algorithms, and databases.

---

### Artifact: Weight Tracker App
The Weight Tracker app was built in my CS360 Mobile Architect & Programming course. It lets users log weight entries, track their goal, and now includes added features through my enhancements.

#### Original version included:
- Login system
- Weight logging
- Goal weight entry
- SMS notifications

<a href="https://github.com/Russrecker/CS-499-Computer-Science-Capstone/tree/main/Artifact-Weight-Tracker/Original" target="_blank">
  <img src="https://img.shields.io/badge/GitHub-Original_Artifact-blue?logo=github" alt="GitHub Repo">
</a>

#### Enhanced version includes:
- Line graph (Software Design and Engineering)
- Merge sort for entries (Algorithms and Data Structures)
- Notes section (Databases)

<a href="https://github.com/Russrecker/CS-499-Computer-Science-Capstone/tree/main/Artifact-Weight-Tracker" target="_blank">
  <img src="https://img.shields.io/badge/GitHub-Enhancements-blue?logo=github" alt="GitHub Repo">
</a>

This artifact works well for my ePortfolio because it ties together multiple areas of computer science into one project.

---

### Enhancement 1 - Software Design and Engineering
For this enhancement, I added a line graph to the Weight Tracker app. The graph pulls data from the database, orders it from oldest to newest, and shows it visually with a goal line. This makes the app more useful because users can see their progress instead of just looking at numbers in a list. On the front end, I integrated MPAndroidChart and customized it with colors, markers, and a goal line. On the back end, I connected it to both the weight and goal databases, made sure the data was sorted correctly, and added error handling. This shows I can connect front-end and back-end work and design a feature that improves usability.

This enhancement also gave me the chance to practice working with outside libraries and tie them into my project in a way that fit my design. I learned how to manage the data flow between the database and the UI, and how to make a visual feature that feels natural for the user. Adding the graph shows that I can take an existing app and build on it with new ideas that improve both the look and the function.

<img src="https://raw.githubusercontent.com/Russrecker/CS-499-Computer-Science-Capstone/main/Artifact-Weight-Tracker/Enhancement%201%20-%20Software%20Design%20and%20Engineering/assets/Line%20Graph.png" alt="Line Graph Screenshot" width="300">

<div style="display:flex; gap:15px;">
  <a href="https://github.com/Russrecker/CS-499-Computer-Science-Capstone/tree/main/Artifact-Weight-Tracker/Enhancement%201%20-%20Software%20Design%20and%20Engineering">
    <img src="https://img.shields.io/badge/GitHub-Enhancement_1-blue?logo=github" alt="GitHub Repo">
  </a>

  <a href="https://github.com/Russrecker/CS-499-Computer-Science-Capstone/blob/main/Artifact-Weight-Tracker/Enhancement%201%20-%20Software%20Design%20and%20Engineering/Narrative.pdf">
    <img src="https://img.shields.io/badge/GitHub-Narrative-blue?logo=github" alt="GitHub Repo">
  </a>
</div>

---

### Enhancement 2 - Algorithms and Data Structures
For this enhancement, I added a merge sort to organize the weight entries. This list can now be sorted by date either newest to oldest or oldest to newest. This makes the app easier to use because users can now look at their progress in whichever order that works best for them. On the front end, I added a popup menu with two choices and a checkmark next to the active option. I Also saved the choice so when users come back, the app remembers how the list was set. On the back end, I converted the date strings into real date objects sos the sorting would work correctly and used merge sort to order the weight entries.

This enhancement gave me practice putting an algorithm into a real app. I learned how to connect sorting logic to the user interface, save user preference, and keep the list updated without issues. Adding merge sort shows that I can take a core computer science concept and apply it to improve usability of my app.

<img src="https://raw.githubusercontent.com/Russrecker/CS-499-Computer-Science-Capstone/main/Artifact-Weight-Tracker/Enhancement%202%20-%20Algorithms%20and%20Data%20Structures/assets/Merge%20Sort.png" alt="Sorting Filter Screenshot" width="300">

<div style="display:flex; gap:15px;">
  <a href="https://github.com/Russrecker/CS-499-Computer-Science-Capstone/tree/main/Artifact-Weight-Tracker/Enhancement%202%20-%20Algorithms%20and%20Data%20Structures">
    <img src="https://img.shields.io/badge/GitHub-Enhancement_2-blue?logo=github" alt="GitHub Repo">
  </a>

  <a href="https://github.com/Russrecker/CS-499-Computer-Science-Capstone/blob/main/Artifact-Weight-Tracker/Enhancement%202%20-%20Algorithms%20and%20Data%20Structures/Narrative.pdf">
    <img src="https://img.shields.io/badge/GitHub-Narrative-blue?logo=github" alt="GitHub Repo">
  </a>
</div>


---

### Enhancement 3 - Databases
For this enhancement, I added a notes database to the Weight Tracker app. This lets users create, read, update, and delete notes. Users can save extra details along with their weight, which makes the app even more useful. On the front end, I added a screen for notes where users can add new notes, edit them, or delete them. If there are no notes, the screen shows a message so the user knows the list is empty. On the back end, I built the database with SQLite, created the table for notes, and set up the queries for each operation.

This enhancement gave me practice working with databases and connecting them to the user interface. I learned how to handle saving and loading data, update the screen when changes are made, and make sure each note is tied to the correct user. Adding the notes database shows that I can build new features that combine front end and back end work and improve the overall functionality of the app.

<img src="https://raw.githubusercontent.com/Russrecker/CS-499-Computer-Science-Capstone/main/Artifact-Weight-Tracker/Enhancement%203%20-%20Databases/assets/Notes.png" alt="Notes Screenshot" width="300">

<div style="display:flex; gap:15px;">
  <a href="https://github.com/Russrecker/CS-499-Computer-Science-Capstone/tree/main/Artifact-Weight-Tracker/Enhancement%203%20-%20Databases">
    <img src="https://img.shields.io/badge/GitHub-Enhancement_2-blue?logo=github" alt="GitHub Repo">
  </a>

  <a href="https://github.com/Russrecker/CS-499-Computer-Science-Capstone/blob/main/Artifact-Weight-Tracker/Enhancement%203%20-%20Databases/Narrative.pdf">
    <img src="https://img.shields.io/badge/GitHub-Narrative-blue?logo=github" alt="GitHub Repo">
  </a>
</div>
