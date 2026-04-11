<sub>All brands, companies and trademarks mentioned are the property of their respective owners.<br>
English is not my native language. Sorry for the mistakes.</sub>

### Hello!

My name is **Yury**. I am a software developer. In my work I use very exotic programming languages, DBMS and other technologies related to programming. Well, that's just how it turned out. I would like to try something that I don't encounter at work now. See how it all developed here: [Blog](https://weekend-game.github.io/blog.htm)

### Viewer of unusual files ([BankViewer](https://github.com/weekend-game/bankviewer))

Java, Swing (Single Document Interface)

My friend receives bank statements in text format, where each field is specified by a key-value pair. He loads these files into the information system. Sometimes problems arise: either the payment date in the statement is indicated in a strange format, or the quantity is loaded instead of the amount, or the required field is not in the file at all. When viewing the file in a text editor, you can find the cause of any problem, but this is very inconvenient. It would be much more convenient to open the file in the program and see the bank statement as a table, where each line is a separate payment. You can immediately see what payments there are, from whom, to whom, what values are written in each column of the table.

This is exactly what this program does. But it also allows you to understand how to create a menu, toolbar, status bar, context menu, file open dialog box, display a file as a table, search, Drag & Drop, use L&F and put it all together as an SDI.

More details here: [BankViewer](https://github.com/weekend-game/bankviewer).

### [Simple library](https://github.com/weekend-game/simplelibrary)

Java, Swing

While creating BankViewer, it became clear that some of the classes needed for this program would be needed in many other similar programs. It would always be necessary to display a message to the user, provide a status bar, localize the application, save some settings, work with Look and Feel, remember recently opened files, have predefined actions for frequently used actions, and be able to quickly and easily place input fields in windows. All of this was concentrated in the game.weekend.simplelibrary package during the development of BankViewer.

Here, I'll extract this package from BankViewer into a separate module for use in future projects.

More details here: [SimpleLibrary](https://github.com/weekend-game/simplelibrary).

### [Text editor](https://github.com/weekend-game/texteditor)

Java, Swing (Single Document Interface), [SimpleLibrary](https://github.com/weekend-game/simplelibrary), [BankViewer](https://github.com/weekend-game/bankviewer) as an application template

So, I created a bank statement viewer. You can create viewers for many other things using a similar approach. But these are just viewers. And if you try to create an editor, you will find that you have to solve many problems. Now I am not creating some unusual editor, I am not creating an editor better than others, I am not trying to compete with anyone. I am researching what problems need to be solved and looking for solutions.

This is a regular text editor that allows you to edit simple text files. It has retained all the features already available in BankViewer. But it not only opens existing files, but also creates new ones, saves edited text, ensures that you do not accidentally lose the result of editing, logically manages the activity of the Edit menu items. It can not only search for text, but also replace one text with another. It allows you to set a convenient font size, use a monospace font if it is convenient in any situation.

More information here: [TextEditor](https://github.com/weekend-game/texteditor).

### [Editor library](https://github.com/weekend-game/editorlibrary)

Java, Swing, [SimpleLibrary](https://github.com/weekend-game/simplelibrary)

Various projects may require the use of a simple text editor as part of the project. A text editor should not only be able to work with text, but also open and save files, search within text, replace words (substrings) with others. This is precisely what the game.weekend.editorlibrary package focused on during the development of TextEditor.

Here, I'll extract this package from TextEditor into a separate module for use in future projects.

More details here: [EditorLibrary](https://github.com/weekend-game/editorlibrary).

### Content Management System ([CMS](https://github.com/weekend-game/cms))

Java, Swing, [SimpleLibrary](https://github.com/weekend-game/simplelibrary)

New project ideas emerge, and every project needs to have its own page on the [website](https://weekend-game.github.io/index.htm). However, adding just one new project requires making changes to all the website's pages. Then, you have to spend a long time checking what you've created. Sure, it's possible, but why?

I am creating my own CMS (content management system) for my website. Problem solved! Sure, I could use something ready-made, but what? And how long would it take me to master it? Would I be able to create the website exactly as I envisioned, or just something like it? I think Java is the best CMS in the world :-)

Furthermore, building this CMS allows me to practice working with Java files and creating a user interface using Swing, specifically: working with text fields, radio buttons, combo boxes, and list editing.

More details here: [CMS](https://github.com/weekend-game/cms).

### To be continued...
