# project-5---adventure-game
**TO GET THIS SOLUTION VISIT:** [Project 5 – Adventure Game](https://www.ankitcodinghub.com/product/project-5-adventure-game/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;10745&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Project 5 - Adventure Game&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Adventure Game

Resources:

CS5044AdventureLibrary.jar

adventure-javadoc.zip

Message.java

MyGameTest.java

Goal

In this program assignment, you will be implementing a text adventure game. You will be working with a number of classes, many of which will be subclasses of existing classes provided for you in the CS5044AdventureLibrary.jar library. You will also be working with interfaces.

Adventure games have been around for a long time, dating back to the Colossal Cave Adventure, (see Colossal Cave Adventure page

(Links to an external site.)

Links to an external site.

, or DG Jerz’s Colossal Cave Adventure page

(Links to an external site.)

Links to an external site.

), but there is more to the history of adventure gaming than this initial spark. In particular, Infocom

(Links to an external site.)

Links to an external site.

was famous as a computer game producer who made text (and later, graphic) adventure games. Zork, their oldest adventure game, is considered by many to be the most famous of all text adventures, or “interactive fiction games”. You can even download and play

(Links to an external site.)

Links to an external site.

Zork I, II, and III. There is even an on-line PHP version

(Links to an external site.)

Links to an external site.

of Zork you can play in your web browser. You can also read the definitive history of Zork

(Links to an external site.)

Links to an external site.

, or read its entry in Wikipedia

(Links to an external site.)

Links to an external site.

.

This assignment offers you a large amount of creative freedom, so do not hesitate to have fun with it!

Learning Objectives

Exposure to object-oriented dispatch

Familiarity with interfaces

Familiarity with creating subclasses

Familiarity with overriding methods

Familiarity with polymorphism

Familiarity with using library classes

Lost In Your Apartment

The game starts off with you in your apartment, and your first goal is to leave. You are in the living room, and going south will take you out of the apartment. But if you try to do that (by entering the command ‘go south’ or ‘south’ or even just ‘s’) you get the following message: “You don’t want to leave your apartment on an empty stomach.” With a little exploration you find that there is peanut butter in the kitchen, which you can eat. Once you have eaten the peanut butter, you can try to leave again, but this time it wants you to lock up your bicycle before you go. Finally, there is a ruby in the bedroom that you have to have with you before the game will let you leave your apartment.

And once you are outside your apartment? Well, that’s up to you. You can create more rooms, more objects, even other people to talk to. You’re only limited by your imagination!

Support Classes Provided for You (DO NOT WRITE THESE!)

Just as in the previous assignments, you have a number of support classes available that will help in constructing an adventure game. These classes are all located in the adventure package, which is provided in the CS5044AdventureLibrary.jar file that is linked to at the top of this page (be sure to add it to your project).

The are four main classes for creating adventure games in the package adventure:

Game represents the main class of a game. It sets the game up, and then enters a loop to read and execute player commands. Note that Game is an abstract class: that means you cannot create an object of this class directly, because some of its methods have not been given definitions. Instead, you must create your own subclass (that extends Game) that defines the missing pieces.

Player represents the person playing the game. The Player class provides minimal features. However, you can create/extend your own custom subclass of Player that adds any new features you wish.

Room represents a location in the game. The Room class provides minimal features. However, you can create/extend your own custom subclass of Room that adds any new features you wish.

Command is an interface that defines the common properties of all command objects. In particular, it requires every command object to implement an execute method. There are three classes that implement this interface that are also provided for you in the adventure package: GoCommand, HelpCommand, and QuitCommand. You can use these three commands, and create any new ones you like.

These four classes (well, three classes and one interface) are the aspects of the adventure package that you will use most often. You will probably need to create your own subclasses of each one at some point, although you can work toward a solution incrementally. Study their javadoc documentation well so that you understand what their methods do.

In addition, the adventure package contains two other classes to help you implement a game:

CommandWords represents a dictionary of known commands in a game. This class uses a Map to associate words with Command objects. This makes it easy to add new commands without affecting the structure of this class.

Parser reads command lines and breaks them up into words, looking the command word up using a CommandWords object. The parser implemented here understands one- and two-word input lines, where a one-word command is a verb (like “quit”), and a two-word command is a verb followed by an object (like “go east” or “take wand”).

In addition to these classes, AdventureGUI is an graphical user interface that contains a large rectangular area for displaying text. There is a smaller rectangle below it where you can enter commands, and a “Move” button that you can press to have the command execute (you should also just be able to hit the [return] key).

Requirements for Your Game Implementation

You will need to extend several classes to implement a base level of required features in your game. Your game implementation must do the following:

Include your own custom subclass of Game. It must be called MyGame.

Include your own custom subclass of Player.

Include your own custom subclass of Room. The four mandatory rooms are “in your living room”, “in your kitchen”, “in your bedroom”, and “outside your apartment”, as shown in the figure above.

Make sure you implement the requirements described in the section “Lost in Your Apartment” above.

Include a variety of locations/rooms (a minimum of 10: the 4 starting rooms + six others). Include a minimum of 3 extra objects (besides the 3 above), and a minimum of 2 extra commands (besides those given below).

It must be possible for a player to reach each of the locations/rooms.

You must extend the basic game to support items. Each item should initially be located in some room. Every room can hold any number of items. Some items can be picked up by the player, others cannot. The player can carry some items with him or her. Every item has a weight. The player can carry items only up to a certain total weight. The three mandatory items are: ruby, bicycle, and peanut-butter. Their starting rooms are shown in the figure above. Make sure you use the hyphenated name “peanut-butter” for the peanut butter. The game does not understand names that include spaces.

The player can win. There has to be some situation that is recognized as the end of the game where the player is informed that he/she has won.

In addition to the go command (which is already implemented for you in the GoCommand class), you must also support the following one-word movement commands: north, south, east, west, up, and down, together with one-letter abbreviations for each: n, s, e, w, u, d. Note: you can support all of these with a single command class, so you will lose points if you use six (or twelve!).

In addition to the commands provided in the adventure package and the movement commands described above, your game should support the following commands:

examine (also x) â€“ Allows you to see the description of an item. This command should work as long as the item is in the same room as you (whether or not you are carrying it).

take â€“ Allows you to take an item from the room and place it in your inventory. Items in the game should have “weights”, so that you can only carry a certain number of items. The bicycle should have the maximum weight, so that you can only carry the bicycle if you are not carrying anything else. The weights of the ruby and peanut-butter should be such that you *can* carry both of them at the same time.

drop â€“ Allows you to remove an item from your inventory and place it in the room.

inventory (also i) â€“ Allows you to view the list of items in your inventory. If there are no items in your inventory, you should get the empty inventory message. If there is at least one item in your inventory, you should get a comma-separated list of items (use the appropriate methods from the Message.java class).

eat â€“ Allows you to eat an object that is edible (like the peanut-butter). You can only eat an item if you are holding it (in other words, if it is in your inventory). When you successfully eat an item it is removed from the game.

lock â€“ Allows you to lock up an item (like your bicycle). If you want to implement an “unlock” method, feel free to do so, but it is not required.

To make it easier to test your game, you must make use of Message.java file. Read the descriptions of the methods and make sure that each message is used in the appropriate place in your game. This file is NOT included in the library, so you will have to create a file named “Message.java” in your project and cut-and-paste the code below into your class. Make sure you do not modify the names of the methods in the file. You may be able to make *small* changes to the text strings without causing problems with the test cases (but use caution if you attempt this!).

Beyond these requirements, you are free to explore any other game features you wish to provide. Feel free to take advantage of this flexibility to have fun while you complete the assignment.

Implementing a “Boring” Adventure Game

To see how to start creating your own game, here is a trivial example of a boring adventure game.

package adventure;

public class BoringGame extends Game {

public BoringGame() {

super(new Player(), new Parser());

}

public static void main(String[] args) {

Game game = new BoringGame();

game.play();

}

@Override

public void createCommands() {

CommandWords commands = parser().commandWords();

commands.addCommand(“go”, new GoCommand());

commands.addCommand(“help”, new HelpCommand(commands));

commands.addCommand(“quit”, new QuitCommand());

}

@Override

public void createRooms() {

// create the rooms

Room outside = new Room(“outside McBryde Hall”);

Room lab = new Room(“in a computing lab”);

// initialise room exits

outside.setExit(“south”, lab);

lab.setExit(“north”, outside);

// the player starts the game outside

player().setCurrentRoom(outside);

}

@Override

public String welcomeMessage() {

return

“&lt;p&gt;Welcome to The World of Simplicity!&lt;/p&gt;”

+ “&lt;p&gt;Type ‘help’ if you need help.&lt;/p&gt;”

+ “&lt;p&gt;Hit [return] to continue…&lt;/p&gt;”;

}

}

Run it (with the library) and see what happens. Remember you have 3 commands “go”, “help”, and “quit”.

Testing Your Game

As with other work in this course, you are responsible for writing tests for all the code you write. In this case, because we have separated the GUI interface from the command processing, we are going to ignore the GUI completely and just test that the commands give you the results in your game that you need. The JUnit test starter file MyGameTest.java sets up your tests so that you can pass multiple commands to a private method (executeMoves), and then check if the resulting room description and message are what you expect them to be. Use the long room description when you want to check whether a room has something in it.

Finally, note that you are expected to (or required to) test the main method of your game subclass. However, if you’ve incrementally tested all your other methods individually, you really only need one very simple test for the main method â€“ its so short that it shouldn’t need anything more than that. You also must write appropriate test cases for all other public methods in all classes that you write, of course.
