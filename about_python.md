# About Python

Python – один из тех редких языков программирования, которые одновременно претендуют на звание _простых_ и _мощных_. Вас приятно удивит то, как легко можно сосредоточиться на решении поставленной задачи, а не на синтаксисе и структуре языка, на котором вы программируете.

Официально Python представляют так:

> Python – это простой в освоении и мощный язык программирования. Он предоставляет эффективные высокоуровневые структуры данных, а также
простой, но эффективный подход к объектно-ориентированному программированию. Его элегантный синтаксис и динамическая типизация наряду с тем, что он является интерпретируемым, делают его идеальным языком для написания сценариев и быстрой разработки приложений в различных областях и на большинстве платформ.

В следующем разделе мы рассмотрим эти особенности более детально.

## История названия

Гвидо ван Россум, создатель языка Python, назвал его так в честь телешоу на BBC под названием «Летающий цирк Монти Пайтона» 1 , а вовсе не потому, что он любит змей, убивающих животных обвиванием своего длинного тела вокруг них и задавливанием.

## Особенности Python

### Простой

Python – простой и минималистичный язык. Чтение хорошей программы на Python очень напоминает чтение английского текста, хотя и достаточно строгого! Такая псевдо-кодовая природа Python является одной из его самых сильных сторон. Она позволяет вам сосредоточиться на решении задачи, а не на самом языке.

### Лёгкий в освоении

Как вы увидите, на Python чрезвычайно легко начать программировать. Python обладает исключительно простым синтаксисом, как уже отмечалось выше.

### Свободный и открытый

Python – это пример свободного и открытого программного обеспечения – _FLOSS_ (Free/Libré and Open Source Software). Проще говоря, вы имеете право свободно распространять копии этого программного обеспечения, читать его исходные тексты, вносить изменения, а также использовать его части в своих программах. В основе свободного ПО лежит идея сообщества, которое делится своими знаниями. Это одна из причин, по которым Python так хорош: он был создан и постоянно улучшается сообществом, которое просто хочет сделать его лучше.

### Язык высокого уровня

При написании программы на Python вам никогда не придётся отвлекаться на такие низкоуровневые детали, как управление памятью, используемой вашей программой, и т.п.

### Портируемый

Благодаря своей открытой природе, Python был портирован на много платформ (т.е. изменён таким образом, чтобы работать на них). Все ваши программы смогут запускаться на любой из этих платформ без каких-либо изменений, если только вы избегали использования системно-зависимых функций.

Python можно использовать в GNU/Linux, Windows, FreeBSD, Macintosh, Solaris, OS/2, Amiga, AROS, AS/400, BeOS, OS/390, z/OS, Palm OS, QNX, VMS, Psion, Acorn RISC OS, VxWorks, PlayStation, Sharp Zaurus, Windows CE и даже на PocketPC!

Вы можете даже использовать такую платформу, как [Kivy](http://kivy.org) для создания игр для вашего компьютера _и_ для iPhone, iPad и Android.

### Интерпретируемый

This requires a bit of explanation.

A program written in a compiled language like C or C\++ is converted from the source language i.e. C or C++ into a language that is spoken by your computer (binary code i.e. 0s and 1s) using a compiler with various flags and options. When you run the program, the linker/loader software copies the program from hard disk to memory and starts running it.

Python, on the other hand, does not need compilation to binary. You just _run_ the program directly from the source code. Internally, Python converts the source code into an intermediate form called bytecodes and then translates this into the native language of your computer and then runs it. All this, actually, makes using Python much easier since you don't have to worry about compiling the program, making sure that the proper libraries are linked and loaded, etc. This also makes your Python programs much more portable, since you can just copy your Python program onto another computer and it just works!

### Объектно-ориентированный

Python supports procedure-oriented programming as well as object-oriented programming. In _procedure-oriented_ languages, the program is built around procedures or functions which are nothing but reusable pieces of programs. In _object-oriented_ languages, the program is built around objects which combine data and functionality. Python has a very powerful but simplistic way of doing OOP, especially when compared to big languages like C++ or Java.

### Расширяемый

If you need a critical piece of code to run very fast or want to have some piece of algorithm not to be open, you can code that part of your program in C or C\++ and then use it from your Python program.

### Встраиваемый

You can embed Python within your C/C\++ programs to give _scripting_ capabilities for your program's users.

### Обширные библиотеки

The Python Standard Library is huge indeed. It can help you do various things involving regular expressions,documentation generation, unit testing, threading, databases, web browsers, CGI, FTP, email, XML, XML-RPC, HTML, WAV files, cryptography, GUI (graphical user interfaces), and other system-dependent stuff. Remember, all this is always available wherever Python is installed. This is called the _Batteries Included_ philosophy of Python.

Besides the standard library, there are various other high-quality libraries which you can find at the [Python Package Index](http://pypi.python.org/pypi).

### Резюме

Python – очень увлекательный и мощный язык. Он имеет хорошее соотношение производительности и возможностей, что делает написание программ на нём одновременно интересным и лёгким.

## Python 3 против 2

You can ignore this section if you're not interested in the difference between "Python version 2" and "Python version 3". But please do be aware of which version you are using. This book is written for Python version 3.

Remember that once you have properly understood and learn to use one version, you can easily learn the differences and use the other one. The hard part is learning programming and understanding the basics of Python language itself. That is our goal in this book, and once you have achieved that goal, you can easily use Python 2 or Python 3 depending on your situation.

For details on differences between Python 2 and Python 3, see:

- [Будущее Python 2](http://lwn.net/Articles/547191/)
- [Портирование кода Python 2 на Python 3](https://docs.python.org/3/howto/pyporting.html)
- [Написание кода, который работает как под Python 2, так и под 3](https://wiki.python.org/moin/PortingToPy3k/BilingualQuickRef)
- [Поддержка Python 3: подробное руководство](http://python3porting.com)

## Что говорят программисты

You may find it interesting to read what great hackers like ESR have to say about Python:

- _Eric S. Raymond_ is the author of "The Cathedral and the Bazaar" and is also the person who coined the term _Open Source_. He says that [Python has become his favorite programming language](http://www.python.org/about/success/esr/). This article was the real inspiration for my first brush with Python.
- _Bruce Eckel_ is the author of the famous 'Thinking in Java' and 'Thinking in C++' books. He says that no language has made him more productive than Python. He says that Python is perhaps the only language that focuses on making things easier for the programmer. Read the [complete interview](http://www.artima.com/intv/aboutme.html) for more details.
- _Peter Norvig_ is a well-known Lisp author and Director of Search Quality at Google (thanks to Guido van Rossum for pointing that out). He says that [writing Python is like writing in pseudocode](https://news.ycombinator.com/item?id=1803815). He says that Python has always been an integral part of Google. You can actually verify this statement by looking at the [Google Jobs](http://www.google.com/jobs/index.html) page which lists Python knowledge as a requirement for software engineers.
