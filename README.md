## Inventory App

<details> 
  <summary>Table of Contents</summary> 
  <ol> 
    <li><a href="#app-summary">App Summary</a></li> 
    <li><a href="#features-and-design">Features and Design</a></li> 
    <li><a href="#my-approach">My Approach</a></li> 
    <li><a href="#testing-process">Testing Process</a></li> 
    <li><a href="#overcoming-challenges">Overcoming Challenges</a></li> 
    <li><a href="#best-component">Best Component</a></li> 
  </ol> 
</details> 

### App Summary
The goal of this project was to create an app that can track items in an inventory. The user required create, read, update, and delete (CRUD) functionality when accessing items in the database. The user also needed to have a unique login and password, and the ability to register a new account if they had not logged in before. The user also receives SMS notifications if an item's quantity is 0 in the inventory.

### Features and Design
The screens required for this app are a login screen, a register new user screen, an inventory screen, an add item screen, and an edit item screen. The user account information and the inventory items both needed to be stored in a database. This lets users keep their data and not have to reenter it every time they access the app. I chose a dark theme for the entire app as I find these easier to read and more pleasant to look at. I also set a consistent color theme throughout the app so that every screen ties into the other screens.

### My Approach
I broke each step down into even smaller parts. For example, the first major function I got working was the login functionality. What did I need to have for that to work? A database. So the first thing I did was create a database for user login information. What did I need the user to be able to do? Create an account. So I added a create new user method in the database. I used this method throughout the development process, just breaking it down into the smallest steps, testing it, and then moving on to the next step.

### Testing Process
To test the app I would run the app in the emulator and do tests on the specific part I was working on to make sure it was working properly. For example, on the login screen I would try several iterations of login attempts, such as no username, no password, and incorrect username and password. This made sure that the checks I coded in were working properly.

### Overcoming Challenges
There were a couple times that I had to make changes to the databases to account for new fields that I hadn't thought of. On more than one occasion this led to the app crashing when I tried to access the database. I tried googling for solutions, but there weren't any cases that specifically matched mine so I ended up using the Android Studio debugger and found out that I was closing the database in the code too early and it was deactivating my cursors. So through persistence I was able to correct a major mistake.

### Best Component
My favorite component of this app is the login screen. I was a graphic designer about 12 years ago so it was fun to be able to use those skills combined with programming to create a functional login screen that looks good and works well.
