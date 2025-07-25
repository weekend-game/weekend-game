<sub>Все упомянутые бренды, компании и товарные знаки являются собственностью их соответствующих владельцев. Имена лиц (кроме моего) являются вымышленными, любые совпадения случайны.</sub>
## Здравствуйте!

Меня зовут Юрий. Работаю программистом. В работе использую весьма экзотические языки, СУБД и прочие связанные с программированием технологии. Ну, так получилось. Хотелось бы попрактиковаться в чём-то, с чем по долгу службы я не сталкиваюсь.

Для начала сделаю нечто совершенно простое. Например, некоторое десктопное приложение, работающее с файлами, с однодокументным интерфейсом ([SDI](https://ru.wikipedia.org/wiki/Однодокументный_интерфейс)). Приложение будет написано с использованием [Java](https://docs.oracle.com/javase/tutorial/index.html). Для создания пользовательского интерфейса использую [Swing](https://docs.oracle.com/javase/tutorial/uiswing/index.html).

Но, что же мне написать? Notepad и Paint уже написаны. Калькулятор? Но с файлами он не работает, да и тоже уже написан. ***Кто же мне поможет с идеей?***

### Друг

Мой друг Андрей получает выписки банка в текстовом формате, где каждое поле задаётся парой ключ-значение. Такие файлы он загружает в некоторую информационную систему. Бывает, что что-то идёт не так. То дата платежа в выписке какая-то странная, то вместо ИНН ОКАТО загружается, а то и вообще, нужного поля в файле не оказывается.
При просмотре такого файла в текстовом редакторе можно найти причину любой проблемы. Но это очень неудобно. Было бы гораздо удобнее, открыть файл в некоторой программе и увидеть банковскую выписку в виде таблицы, где каждая строка будет платежом. Сразу будет видно, что там за платежи, от кого, кому, и вообще, какие значения записаны в каждой колонке таблицы.
Мы с Андреем договорились о следующем. За такую прекрасную идею простой программы с интерфейсом SDI, работающей с файлами я эту программу напишу, передам Андрею, денег за неё не получу, могу делать с этой прогой, что мне заблагорассудится. Согласитесь, выгодное предложение! Ну, а что из этого получилось, смотрите тут [BankViewer](https://github.com/weekend-game/bankviewer).
