# CS 499 Computer Science Capstone

### Professional Self-Assessment
Hi, my name is Russell Reckhow and I am finishing up my bachelor's degree in Computer Science at Southern New Hampshire University. When I started this program, I had little to no background in computer science. Over time I learned new skills and built projects that show I can design, code, and solve problems. Working on the Capstone gave me the chance to see how much I’ve improved since starting the program.

Some of my favorite classes gave me the chance to work on cool projects and see how computer science applies in different ways. In CS-330 Computer Graphics and Visualization, I built a 3D OpenGL scene that showed me how graphics work in programming. In CS-465 Full Stack Development, I worked on the Travlr Getaways project, where I used the MEAN stack and learned how the front-end and back-end work together. In CS-370 Current & Emerging Trends in CS, I built a reinforcement learning pirate agent to find the fastest way to the treasure. These classes gave me hands-on experience and helped me grow my skills in different areas of computer science.

The program also gave me the chance to connect with other classmates through discussions and the unofficial school Discord. I was able to talk with other students, get and share feedback, which made me think about problems in new ways. This helped me see how important it is to communicate with your peers, since explaining your thought process and listening to others can make things easier.

The program also helped me build skills that I’ll take with me, whether in a computer science career or another path I decide to follow. I learned how to make my code run better with the right algorithms, how to design apps in a way that makes sense for users, and how to work with databases to store and pull data. I also started paying more attention to security, like checking inputs and avoiding mistakes that could cause problems. These are all things I know will carry over into real projects.

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

### [Artifact: Weight Tracker App](https://github.com/Russrecker/CS-499-Computer-Science-Capstone/tree/main/Artifact-Weight-Tracker)
The Weight Tracker app was built in my CS360 Mobile Architect & Programming course. It lets users log weight entries, track their goal, and now includes added features through my enhancements.

#### Original version included:
- Login system
- Weight logging
- Goal weight entry
- SMS notifications

#### Enhanced version includes:
- Line graph (Software Design and Engineering)
- Merge sort for entries (Algorithms and Data Structures)
- Notes section (Databases)

This artifact works well for my ePortfolio because it ties together multiple areas of computer science into one project.

---

### [Enhancement 1 - Software Design and Engineering](https://github.com/Russrecker/CS-499-Computer-Science-Capstone/tree/main/Artifact-Weight-Tracker/Enhancement%201%20-%20Software%20Design%20and%20Engineering)
For this enhancement, I added a line graph to the Weight Tracker app. The graph pulls data from the database, orders it from oldest to newest, and shows it visually with a goal line. This makes the app more useful because users can see their progress instead of just looking at numbers in a list. On the front end, I integrated MPAndroidChart and customized it with colors, markers, and a goal line. On the back end, I connected it to both the weight and goal databases, made sure the data was sorted correctly, and added error handling. This shows I can connect front-end and back-end work and design a feature that improves usability.

This enhancement also gave me the chance to practice working with outside libraries and tie them into my project in a way that fit my design. I learned how to manage the data flow between the database and the UI, and how to make a visual feature that feels natural for the user. Adding the graph shows that I can take an existing app and build on it with new ideas that improve both the look and the function.

<img src="https://raw.githubusercontent.com/Russrecker/CS-499-Computer-Science-Capstone/main/Artifact-Weight-Tracker/Enhancement%201%20-%20Software%20Design%20and%20Engineering/assets/Line%20Graph.png" alt="Line Graph Screenshot" width="300">

---

### [Enhancement 2 - Algorithms and Data Structures](https://github.com/Russrecker/CS-499-Computer-Science-Capstone/tree/main/Artifact-Weight-Tracker/Enhancement%202%20-%20Algorithms%20and%20Data%20Structures)
For the enhancement, I added a merge sort to organize the weight entries. This keeps the graph and list view consistent and shows that I can apply algorithms in practice. It also gave me the chance to compare built-in sorting with implementing an algorithm directly. This enhancement shows that I can solve problems with data and improve efficiency where needed. 

<img src="https://raw.githubusercontent.com/Russrecker/CS-499-Computer-Science-Capstone/main/Artifact-Weight-Tracker/Enhancement%202%20-%20Algorithms%20and%20Data%20Structures/assets/Merge%20Sort.png" alt="Sorting Filter Screenshot" width="300">

---

### [Enhancement 3 - Databases](https://github.com/Russrecker/CS-499-Computer-Science-Capstone/tree/main/Artifact-Weight-Tracker/Enhancement%203%20-%20Databases)
I built a notes section that uses the SQLite database. Now users can save comments or details such as their meals, workout or maybe even how they felt that day. This enhancement gave me experience designing a table, connecting it with the app, and making sure new data shows right away. It shows that I can design and manage databases inside an application.

<img src="https://raw.githubusercontent.com/Russrecker/CS-499-Computer-Science-Capstone/main/Artifact-Weight-Tracker/Enhancement%203%20-%20Databases/assets/Notes.png" alt="Notes Screenshot" width="300">
