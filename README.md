# jVideo
The sole purpose of me creating this was programming practice with the Java language. 
I still thought it would be best to make it available to the public incase someone would like to point out areas of improvement in my code(which there is always place for) so do send me criticism or maybe features you'd like to see added!
>What I will NOT do is explain what the program does nor how to use it. You will have to figure that out on your own. 
>But what I will explain is how to get the program up running because I feel like thats the bare minimum I should do.

## Required:
| What | Where |
| ---- | ----- |
| My Program | Download [Here](https://mega.nz/file/H4NBBCpD) |
| Java(SE 11+) | Download from Oracle [Here](https://www.oracle.com/java/technologies/javase-downloads.html) |
| XAMPP | Download from Apache Friends [Here](https://www.apachefriends.org/download.html) |

#### Decryption Key: 
- Lyc5u1Cm41HacPgRZjBcksV4HwhOK6vcPCa_7YWnE2A

Once You have downloaded and installed everything above open a command terminal and check that the correct version of Java(Anything above Java SE 11) is being used by your system. If its not follow [This](https://confluence.atlassian.com/doc/setting-the-java_home-variable-in-windows-8895.html) tutorial on how to make it do so.
>If you are on Windows you could just use the included SetJavaVersion(WINDOWS).bat file to set Java to the correct version. What you have to first do is Right-Click the file -> Edit -> and change "JAVA_HOME=" to the location of whatever Java version you downloaded. If you downloaded version 11.0.9 then you dont have to change anything before running the file.

## Setup:
- Open XAMPP and start the Apache & MySQL Modules. Make sure that the MySQL server is on port 3306.

- Open your favorite browser and head over to ``` http://localhost/phpmyadmin/index.php ``` and create a new database with the name custom_database.

- Drag and drop the 3 SQL files included(in the jVideo.rar file you downloaded above) into the newly created database. Three new tables should appear in your database called ``` all_videos ``` , ``` filtered_list ``` , and ``` secondary_filtered_list ```.

- Launch my program(by double clicking the jVideo.jar file...) and 3 files will be created in whatever directory my program is in. You can take a guess at what each of those files is used for.

- Go to the Settings tab and make sure the database information is correct.

- ## Figure the rest out on your own :)


###### If you require any help or run into any issues with my program feel free to message me :)
