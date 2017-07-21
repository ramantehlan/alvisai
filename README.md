# AlvisAI
Alvisai is a social networking web app with a built in bot. 


# Back Story
#### You probably don't want to read it


This web app was designed and developed by me and was launched officially in **2015** with a *vision to help out people in depression, people who are shy to talk about their problems.* I had this vision when I saw my own school friends facing depression issues.


That's when I decided to create a social network with artificial intelligence, a network which could understand your emotions and help you when you feel troubled about something, a network which could talk to you like a human; like a friend. This social network has features like anonymous updates and options to tag your emotions, which are specifically made for shy and depressed users. This app also learns to understand emotions by creating a network between the emotional tags used and then matching them with the kind of words and images they are updating.


But unfortunately, my vision/app didn't get much response, not many people signed up for it and it did a crash landing. I later wrote a (private)document on what went wrong. It was my approach to the problem which didn't fit right. I had to learn it hard way. The irony is that after this I myself got a bit depressed and was disappointed, well I was 16 or 17 maybe and was too excited about this project, so disappointment was quite guaranteed. But I learned a lot and was quite happy and positive in the end. 


#### What's in it for you.
Well, after 2 years I have decided to open source my web app and if you need a pre-built social network then feel free to use AlvisAI.


# Installation


**1) Download the project to root directory.**


Download the project and unzip only in the root directory of your website root or localhost.


**2) Import database to MySQL.**


You need to import two **.sql** files to MySQL database. Those two files are: `server/sql/alvisai.sql` and `server/sql/alvisai_learn.sql` in the root directory.


> Note: Till this step, The social networking will get active but it won't have a bot yet. Now we will use [**Program-O**](https://github.com/Program-O/Program-O), which is pre-installed in root directory we just need to initiate bot installation.


## Installing Program-O


**3) Create bot database**


Create a new database in MySQL, name it "alvis_bot".


**4) Install Bot**


Go to `http://host/ai_box/ai/program_o/install/install_programo.php` where the host can be localhost or your website. Then the installation form will appear. Fill out this form and use "alvis_bot" as its database and other details according to your MySQL database. Finally, click on save.

> Note: Bot will work now but you still need to teach your bot. To do that just got to **http://host/ai_box/ai/program_o/admin/** and log in with your Program-O details which you filled in step `Install Bot`.

**That's it! AlvisAI is alive now** :sparkles: :boom: :sparkles: :boom:



