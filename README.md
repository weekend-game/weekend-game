<sub>All brands, companies and trademarks mentioned are the property of their respective owners.<br>
English is not my native language. Sorry for the mistakes.</sub>


### Hello!

My name is **Yury**. I am a programmer. In my work I use very exotic programming languages, DBMS and other technologies related to programming. Well, that's just how it turned out. I would like to try something that I don't encounter at work now. See how it all developed here: [Diary](https://weekend-game.github.io/diary.htm)

### Viewer of unusual files ([BankViewer](https://github.com/weekend-game/bankviewer))

Java, Swing (Single Document Interface)

My friend receives bank statements in text format, where each field is specified by a key-value pair. He loads these files into the information system. Sometimes problems arise: either the payment date in the statement is indicated in a strange format, or the quantity is loaded instead of the amount, or the required field is not in the file at all. When viewing the file in a text editor, you can find the cause of any problem, but this is very inconvenient. It would be much more convenient to open the file in the program and see the bank statement as a table, where each line is a separate payment. You can immediately see what payments there are, from whom, to whom, what values are written in each column of the table.

This is exactly what this program does. But it also allows you to understand how to create a menu, toolbar, status bar, context menu, file open dialog box, display a file as a table, search, Drag & Drop, use L&F and put it all together as an SDI.

More details here: [BankViewer](https://github.com/weekend-game/bankviewer).

### Text editor ([WeekendTextEditor](https://github.com/weekend-game/weekendtexteditor))

Java, Swing (Single Document Interface), [BankViewer](https://github.com/weekend-game/bankviewer) as an application template

So, I created a bank statement viewer. You can create viewers for many other things using a similar approach. But these are just viewers. And if you try to create an editor, you will find that you have to solve many problems. Now I am not creating some unusual editor, I am not creating an editor better than others, I am not trying to compete with anyone. I am researching what problems need to be solved and looking for solutions.

This is a regular text editor that allows you to edit simple text files. It has retained all the features already available in BankViewer. But it not only opens existing files, but also creates new ones, saves edited text, ensures that you do not accidentally lose the result of editing, logically manages the activity of the Edit menu items. It can not only search for text, but also replace one text with another. It allows you to set a convenient font size, use a monospace font if it is convenient in any situation.

More information here: [WeekendTextEditor](https://github.com/weekend-game/weekendtexteditor).

### Programming language interpreter ([WeekendInterpreter](https://github.com/weekend-game/weekendinterpreter))

Java, Swing (Single Document Interface), [WeekendTextEditor](https://github.com/weekend-game/weekendtexteditor) as an application template

I'm increasing the difficulty. In fact, a programmer should fight complexity (Steve McConnell. Code Complete. Chapter 34: Themes in Software Craftsmanship), but this is true for program texts. And I complicate the task.

Creating your own programming language is a useful thing. Firstly, it is interesting. Secondly, it can be used, for example, for acceptance testing, that is, for writing acceptance tests (Robert C. Martin. Agile Software Development: Principles, Patterns, Practices. Chapter 4. Testing. "Acceptance  tests  are  programs  and  are  therefore  executable.  However, they  are usually written in a special scripting language created for customers of the application."). Or, for example... Have you tried to write a program for calculating wages? Some accruals, deductions, and all this depends on a huge number of conditions. Of course, you can take all this into account, program it. Or you can give the accountant a simple language for describing the calculation rules. The main thing is not to tell the accountant the words "programming language", but to call it "setting up" accruals and deductions. :)

So, I take my editor and divide its central part into two parts: in the upper part I leave the editor, and place a panel at the bottom that will display everything that my interpreter outputs. Then I add the "Run" menu with the "Run" and "Stop" items...

More details here: [WeekendInterpreter](https://github.com/weekend-game/weekendinterpreter).

### A game in a new language ([AspenForest](https://github.com/weekend-game/aspenforest))

Weekend Game Language, [WeekendInterpreter](https://github.com/weekend-game/weekendinterpreter)

Since I've created a [programming language](https://github.com/weekend-game/weekendinterpreter), why not write something interesting in it and experience what it's like to write in such a language? I'll take a break from algorithms and interpreter writing techniques and write a program in the language I created. 

It's a small text-based game. A knight walks through an aspen forest. He meets different situations and must decide how to act in each one. The game has no music or graphics. The current language implementation simply doesn't allow for such features. However, nothing prevents them from being added. If WeekendInterpreter is Hello World for interpreter developers, then AspenForest is Hello World for text-based games, plus an attempt at using a new (actually very old) language.

More information here: [AspenForest](https://github.com/weekend-game/aspenforest).

### Content Management System (CMS) ([WeekendCMS](https://github.com/weekend-game/weekendcms))

Java, Swing, a few classes taken from previous projects (GBL, Loc, Mes, Proper)

I ran into a problem. On August 23, 2025, while relaxing on the beautiful Mediterranean coast in Side, I designed and implemented a template for my [website](https://weekend-game.github.io/index.htm). I planned to publish full descriptions of all the projects I publish here. And, well, it all worked out. I came up with a bilingual homepage, decided to dedicate a page in each language to each project (repository), and started a [diary](https://weekend-game.github.io/diary.htm). Yes, I haven't written everything I wanted on these pages yet, but I definitely will. And life goes on. So, I designed and implemented a game, albeit a small one, in my own programming language. And it's time to work on applications that work with various DBMSs. How much longer can I use the Proper class (anyone who's looked at projects knows what I mean)? The poor thing (I'm talking about the Proper class) must have suffered greatly. But all of this needs to have its own page on the website. Adding just one new page requires changes to all pages of the site. Sure, it's possible, but why?

I created my own CMS (content management system) for my website. Problem solved! Sure, I could use a ready-made one, but which one? And how long would it take me to master it? Will I be able to create the site exactly the way I envisioned, set on the Mediterranean coast or something similar? So, the job is done: the CMS is created, and it works. As for further customization of this CMS to my needs, in my opinion, nothing compares to Java for flexibility.

More details here: [WeekendCMS](https://github.com/weekend-game/weekendcms).

### Seed Keeper ([SeedKeeper](https://github.com/weekend-game/seedkeeper))

Java, [JavaFX](https://openjfx.io/) (Tabbed document interface), DBMS [Apache Derby](https://db.apache.org/derby/)

Thanks to Swing, but I'll try JavaFX now. It's a six of one, half a dozen of the other, I suppose, but it's interesting to try. There will be a lot of data... and anyway, it's time to practice working with different DBMSs.

My wife gave me the idea for this app. She grows tomatoes, peppers, and other plants as a hobby. She buys packets of seeds and grows a few plants of each variety. Often, she has leftover seeds, and sometimes we buy a variety but can't plant it that season. We're programmers, not farmers, and we have very little space to grow tomatoes.

So, she accumulated several thousand packets of seeds, and we need to track them on our computer. A spreadsheet is impossible: the plant photos alone take up over 10 GB. A spreadsheet would do the job, but it would be incredibly slow. So my wife came up with a program to track these thousands of packets.

And I need to practice with the database (**Apache Derby**), try out a development new type of user interface (**Tabbed document interface**), a new UI development kit (**JavaFX**), and figure out how to create such a program in a few hundred lines. At the same time, the conciseness of the code must not compromise the user interface and the necessary functionality.

More details here: [SeedKeeper](https://github.com/weekend-game/seedkeeper).

### To be continued...
