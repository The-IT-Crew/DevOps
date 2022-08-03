#  🐍 Introduction to DevOps

**2. Devops Stages**

<h2> Version Control</h2>

<p>Version control is a set of practices and tools for managing codebases. Developers use version control to keep track of every line of code, and share, review, and synchronize changes among a team. We are gonna focus on Git here.</p>

<p> Other version control tools like-

- Mercurial

- Apache Subversion (SVN)

- Concurrent Version Systems (CVS)

- Perforce

- Bazaar

- Bitkeeper

- Fossil

<img src='../Images/image1.png' alt='chart'>

<p><h3>How the Centralized version control system works ?</h3></p>

<img src='../Images/image2.png' alt='cvcs'>

<p>Centralized control version system only has 2 repositories a master repositories and client repositories.</br>

The server act as a master repositories and developers personal workspace acts as a client repositories. Everytime the user/client

need to be on the same network to access the master repositories because you can't access it remotely. User/Client commits directly to the <code> main </code> branch.

Centralized version control system basically used for small team member and large file commits.</p>

<h3>Advantages of CVCS</h3>

<hr>

<p>When a developer chnages to the bulid and push it to the server repositories there should be a commit message, showing who and which exact file they changed and where did actually the code changed. </p>

<p> Binary files, such as graphic assets and text files, require a large amount of space, so software developers turn to centralized version control systems to store this data. With a centralized server, teams can pull a few lines of code without saving the entire history on their local machine. Users of distributed systems have to download the entire project, which takes up time and space and prevents them from doing diffs. If a team works with binary files regularly, a centralized system offers the most efficient approach to code development.</p>

###  Disadvantage of CVCS

<hr>

<p>All the system main files and metadata are stored in to an single repositories. If, somehow the server's main repositories crashed or get corrupted, all the system files would be lost,</p>

<p>Also, u can't access the data form server remotely, you will always need to be on a specific network to access it.</p>

<h3>How the Distributed version control system works ?</h3>
<img src='../Images/image4.png' alt='dvcs'>
 - Every workstation developer has a copy of a main repositories on their local Hard-Drive, developer can fetch data from main repositories to their local repositories, edit the contents of local repositories, commit and push it back to the central/main/remote repositories.
 - If somehow the server side repo/main repositories get crashed or corrupted,every developer has a local copy of that main repositories on their hard-drive. So, data loss should't be a issue.
<img src='../Images/image5.png' alt='dvcs1'>
<p>Every new content u can pull form the server side repositories and after changes you can push into the server repositories.

