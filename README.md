# SnakeFinal

This is a simple snake game that we've been working on for a little while. Here's a brief rundown of the version history in this repository.

# Snake 2.0 (refactored)

This code is based off of the code found in this: (https://github.com/MrNeonMan123/Brandon/blob/master/Snake%202.0.zip) repository. It has near identical functionality, but I find the refactored version much easier to read in several ways.

# Snake 2.1

This version added a significant number of additional features, namely user selection of different settings. Specifically, it added various map sizes, speeds which alter difficulty, and a setting which gradually increases the speed of the snake, as well as some user-friendly UI improvements.

# Snake 2.2

(most recent version)

I had to upload this as a compressed zip file, as it included a slew of new files that came along with adding a SqlServer database to the equation. I added functionality which allows a user to enter a 3 character username which records their score, and a method (albeit unimplemented) that allows a user to read the top 10 scores to the console. I'm not sure if the database will work for other users, however, as the connection string has a path specific to the files in MY pc.

# Snake 2.2.1

Solved the issue where the connection string was only configured for my computer. Made some other refactorings and changes.

# Snake 2.2.2

Made some significant UI changes and attempted to implement the Top Ten scores feature, but ran into some issues with the SQL code which wouldn't allow me to use a SELECT statement. Working on a fix, and when implemented will post as version 2.3 .
Completely refactored the logic of the program, instead of existing within loops under one piece of code, it is now factored into many classes and methods. This is both easier to understand and complient with the Single Responsibility Principle.

# Snake 2.2.3

Added a score counter and some other minor fixes and improvements.

# Snake 2.3

What an exciting update! I found the error in my C# database implementation (I missed a space in between a variable name and a keyword) and now everything is functioning as intended. This completes the basic implementation of the database, which is why I am proud to announce that this version is the long-awaited version 2.3 .

# Snake 2.3.1

(most recent version)

Bug fixes and UI improvements!

# Future Plans

Snake 2.4 may include either an online database (unlikely to be honest) or some minor UI and other improvements.
