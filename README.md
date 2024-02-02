# Google Classroom API
This repository will be the basis for our independent work in class developing our coding expertise through hands on real world activities.
## Understanding the Quickstart
The QuickStart is provided as an example by Google primarily to demonstrate to developers how to set up and authorize projects using Google APIs. You can find it at [Google Classroom java quickstart](https://developers.google.com/classroom/quickstart/java).
1. Accept the GitHub classroom assignment.
2. Copy the link to your repository.
3. Open IntelliJ and open the project from VCS
4. Use the link from step 2. You may need to regenerate a token.
5. Once the project is open then find the main file [Quickstart.java](src/main/java/ClassroomQuickstart.java) and run it. It may take some time for it to download and build all the required pieces.

The code makes use of your web browser to get access to your Google Classroom account. Once you have accessed your account it stores an [access token](tokens/StoredCredential) on your computer.

Note that this all works because I have gone through the steps to register this program with Google. These steps are listed in the Quickstart.

If you were successful then you will see a list of your active Google Classroom classes.
