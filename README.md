# Pet Game（Group 77)

## Overview
This virtual Pet Game software is a pet raising simulation. It lets users add and delete pets which they can interact through feeding, playing, exercising, visiting the vet, gifting, and putting to bed. It also allows a admin/parent to set a password for the admin screen and through there, revive a pet, set allowed hours, and view playtime statistics. 

## Required Libraries and Third-Party Tools
    To build and run the software, the following libraries and third-party tools are required:

        - Java JDK (version 23.0.2): Required to compile and run Java programs.
        - NetBeans IDE (version 25): Integrated development environment for building Java applications, recommended for compiling and running the project.
        - Maven (version 3.x or higher): Apache Maven is used for project management and building the project.
        - Java Swing: Used for the graphical user interface (GUI). It is included in the standard Java Development Kit (JDK).

    Dependencies:
        - JUnit 5: For unit testing.
            - `junit-jupiter-api` version 5.10.3
            - `junit-jupiter-params` version 5.10.3
            - `junit-jupiter-engine` version 5.10.3
        - AbsoluteLayout (for UI components, from NetBeans external libraries):
            - `AbsoluteLayout` version RELEASE250

## Building the Software
    Prerequisites:
        1. Ensure you have JDK 23.0.2. If not download JDK here: https://www.oracle.com/java/technologies/javase/23-0-2-relnotes.html
        2. Open NetBeans IDE (version 25) or download if missing: https://netbeans.apache.org/front/main/download/nb25/
        3. Confirm Maven installed in NetBeans IDE (Java SE version of Netbeans includes Maven support by default)
    Steps to Build:
        1. Select Open Project in NetBeans IDE and open petGameDemo.
        2. Under the Netbeans IDE Projects tab, the source packages, test packages, dependecies, and project files folders should be visible.
        3. Click into the source package, then expand com.mycompany.petgame.
        4. Inside com.mycompany.petgame, there should be a file with a green play arrow beside it called GameManager.java.
        5. Double click on GameManager.java so it opens in the editor and click the hammer icon in the toolbar near the top of the screen.
        6. The output tab should output "BUILD SUCCESS"
    Find .jar file after building:
        1. Under petGameDemo folder, there should be another folder called target. This is where you will find the .jar file you can run.
        2. There is a Fat JAR (aka. uber JAR) that includes all project dependencies called "petGameDemo-1.0-jar-with-dependencies.jar". You can double click this to run or enter "java -jar petGameDemo-1.0-jar-with-dependencies.jar" into the console or terminal.

## How to run built, compiled software
    1. Under petGameDemo folder, there should be another folder called target. This is where you will find the .jar file you can run.
    2. Since the code in the pom.XML is configured to create a Fat JAR (aka. uber JAR), you can just double click the .jar named "petGameDemo-1.0-jar-with-dependencies.jar" to run it or run it in the console or terminal through "java -jar petGameDemo-1.0-jar-with-dependencies.jar".

## How to use the software
    Once you have double clicked the jar file, you will be met with various options you can choose from. These include Tutorial, Parental Controls, New Game, and Load Game.
    If you are new to the game, you can click through the tutorial to learn more about how the game works.
    If you are a parent and want to moderate how another user is playing the game, you can use the parental controls to place time constraints on when the user is playing the game, see stats on playtime, and revive pets if needed.
    Clicking load game will allow you to load from up to three pre-existing games.
    To begin a new game, press new game, select a pet, and give it a name. Then save it to a save file of your choice. Each pet has unique attributes. 
    As a user, you are able to interact with your pet in various ways, such as taking them to the vet, feeding them, gifting them, playing with them, and telling them to go to sleep. 

    Once in the main gameplay screen, you’ll see your pet and its stats:
    Health: Indicates your pet’s overall well-being. Health is replenished by going to the vet.
    Hunger: Replenished by feeding.
    Happiness: Improved by playing with or gifting items to your pet.
    Sleep: Replenished by sending your pet to sleep.
    All of the stats will slowly decrease over time. It is important to try not to let any of the stats go to 0. If your health goes to 0, the pet will die. If sleep falls to 0, then the Pet will fall asleep. If hunger goes to 0, health will begin to decline. If happiness goes to 0, your Pet will be angry and will refuse most commands. 
    In order to receive items to feed your pet, you can play the minigame. The minigame is a classic card matching game. Successfully winning the minigame by matching all of the cards will reward players with an inventory item. Successfully completing an easy game will reward players with a one-star item, a medium game will reward players with a two-star item, and a hard game will reward players with a three-star item. 
    You can access the inventory through the inventory button on the playing screen.
    The more stars an item has, the more of an impact it will have on the pet. You can see the impact the item will have on your pet by hovering over the document icon. 
    The game will automatically save every 15 minutes. You can also load a previously saved game from the main menu. Players can save to one of three slots and switch between different pets. They can also override save slots if they wish to do so. 
    There are also shortcuts for accessibility. You can press esc to go back to the main menu, F for feed, P for play, etc. A full list of the shortcuts can be found within the tutorial. 
    If your game dies, the player can either revive the pet through parental controls or start a new game. 

## Required Usernames and Passwords 
    Though the Parental Controls page is password-protected, when going through the initial set up the password is set by the user. It is important to keep this password in a safe place so you can refer back to it.  There are no pre-existing required usernames and passwords.

## Access Parental Controls
    1. To access the Parental Controls Screen, you will be required to enter a password. This password is set by the user the first time they open up the software. Make sure to remember this password as you will not be able to reset it. There will be no need to build or install it as it is built into the game.