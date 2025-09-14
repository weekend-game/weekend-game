<sub>All brands, companies and trademarks mentioned are the property of their respective owners.<br>
English is not my native language. Sorry for the mistakes.</sub>


### Hello!

My name is Yury. I am a programmer. In my work I use very exotic programming languages, DBMS and other technologies related to programming. Well, that's just how it turned out. I would like to try something that I don't encounter at work now. See how it all developed here: [Diary](https://weekend-game.github.io/diary.htm)

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

### A game in a new language and its interpreter ([AspenForest](https://github.com/weekend-game/aspenforest))

Weekend Game Language, [WeekendInterpreter](https://github.com/weekend-game/weekendinterpreter)

Since I have created some programming language, why not write something interesting in it, and at the same time feel what it is like to write in such a language. I will distract myself from algorithms and methods of writing interpreters and will write a program in the created language.

It's a small text game. A knight walks through an aspen forest. He encounters different things and has to make decisions about how to act in a given situation. There is no music or graphics in the game. The current language implementation simply does not allow for anything like that. Although nothing prevents these features from being added. And if WeekendInterpreter is Hello World for interpreter developers, then AspenForest is Hello World for text games, plus an attempt to use a new (actually very old) language.

More information here: [AspenForest](https://github.com/weekend-game/aspenforest).
