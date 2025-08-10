<sub>All brands, companies and trademarks mentioned are the property of their respective owners.<br>
English is not my native language. Sorry for the mistakes.</sub>


### Hello!

My name is Yury. I am a programmer. In my work I use very exotic programming languages, DBMS and other technologies related to programming. Well, that's just how it turned out. I would like to try something that I don't encounter at work now.

### Viewer of unusual files ([BankViewer](https://github.com/weekend-game/bankviewer))

[Java](https://docs.oracle.com/javase/tutorial/index.html), [Swing](https://docs.oracle.com/javase/tutorial/uiswing/index.html) **(Single Document Interface)**

My friend receives bank statements in text format, where each field is specified by a key-value pair. He loads these files into the information system. Sometimes problems arise: either the payment date in the statement is indicated in a strange format, or the quantity is loaded instead of the amount, or the required field is not in the file at all. When viewing the file in a text editor, you can find the cause of any problem, but this is very inconvenient. It would be much more convenient to open the file in the program and see the bank statement as a table, where each line is a separate payment. You can immediately see what payments there are, from whom, to whom, what values are written in each column of the table.

This is exactly what this program does. But it also allows you to understand how to create a menu, toolbar, status bar, context menu, file open dialog box, display a file as a table, search, [D&D](https://en.wikipedia.org/wiki/drag_and_drop), use [L&F](https://en.wikipedia.org/wiki/Look_and_feel) It allows you to understand how to combine all this in SDI.

More details here: [BankViewer](https://github.com/weekend-game/bankviewer).

### Text Editor ([WeekendTextEditor](https://github.com/weekend-game/weekendtexteditor))

[Java](https://docs.oracle.com/javase/tutorial/index.html), [Swing](https://docs.oracle.com/javase/tutorial/uiswing/index.html) **(Single Document Interface)**, [BankViewer](https://github.com/weekend-game/bankviewer) as an application template

So, I created a bank statement viewer. You can create viewers for many other things using a similar approach. But these are just viewers. And if you try to create an editor, you will find that you have to solve many problems. Now I am not creating some unusual editor, I am not creating an editor better than others, I am not trying to compete with anyone. I am researching what problems need to be solved and looking for solutions.

This is a regular text editor that allows you to edit simple text files. It has retained all the features already available in BankViewer. But it not only opens existing files, but also creates new ones, saves edited text, ensures that you do not accidentally lose the result of editing, logically manages the activity of the Edit menu items. It can not only search for text, but also replace one text with another. It allows you to set a convenient font size, use a monospace font if it is convenient in any situation.

More information here: [WeekendTextEditor](https://github.com/weekend-game/weekendtexteditor).

### Programming language interpreter ([WeekendInterpreter](https://github.com/weekend-game/weekendinterpreter))

[Java](https://docs.oracle.com/javase/tutorial/index.html), [Swing](https://docs.oracle.com/javase/tutorial/uiswing/index.html) **(Single Document Interface)**, [WeekendTextEditor](https://github.com/weekend-game/weekendtexteditor) as an application template

I complicate the program. In fact, a programmer should fight complexity (Steve McConnell. Code Complete. Chapter 34: Themes in Software Craftsmanship), but this is true for program texts. And I complicate the task.

Creating your own programming language is a useful thing. Firstly, it is interesting. Secondly, it can be used, for example, for acceptance testing, that is, for writing acceptance tests. Or, for example... Have you tried to write a program for calculating wages? Some accruals, deductions, and all this depends on a huge number of conditions. Of course, you can take all this into account, program it. Or you can give the accountant a simple language for describing the calculation rules. The main thing is not to tell the accountant the words "programming language", but to call it "setting up" accruals and deductions. :)

So, I take my editor and divide its central part into two parts: in the upper part I leave the editor, and in the lower part I output everything that my interpreter outputs. Then I add the Run menu with the Run and Stop items.

More details here: [WeekendInterpreter](https://github.com/weekend-game/weekendinterpreter).

