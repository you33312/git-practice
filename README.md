# git-practice
Windows PowerShell
Copyright (C) Microsoft Corporation. All rights reserved.

Install the latest PowerShell for new features and improvements! https://aka.ms/PSWindows

PS C:\Users\ASUS>  ssh-keygen -t rsa -C "pavlo.kabal.24@pnu.edu.ua"
Generating public/private rsa key pair.
Enter file in which to save the key (C:\Users\ASUS/.ssh/id_rsa): cat ~/.ssh/id_rsa.pub
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Saving key "cat ~/.ssh/id_rsa.pub" failed: No such file or directory
PS C:\Users\ASUS> it config --global user.email "pavlo.kabal.24@pnu.edu.ua"
It : Cannot process argument transformation on parameter 'test'. Cannot convert the "--global" value o
f type "System.String" to type "System.Management.Automation.ScriptBlock".
At line:1 char:11
+ it config --global user.email "pavlo.kabal.24@pnu.edu.ua"
+           ~~~~~~~~
    + CategoryInfo          : InvalidData: (:) [It], ParameterBindingArgumentTransformationException
    + FullyQualifiedErrorId : ParameterArgumentTransformationError,It

PS C:\Users\ASUS> cd Desktop
PS C:\Users\ASUS\Desktop> git clone git@github.com:КабальПавло/git-practice.git
git : The term 'git' is not recognized as the name of a cmdlet, function, script file, or operable pro
gram. Check the spelling of the name, or if a path was included, verify that the path is correct and t
ry again.
At line:1 char:1
+ git clone git@github.com:КабальПавло/git-practice.git
+ ~~~
    + CategoryInfo          : ObjectNotFound: (git:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\ASUS\Desktop> cd git-practice
cd : Cannot find path 'C:\Users\ASUS\Desktop\git-practice' because it does not exist.
At line:1 char:1
+ cd git-practice
+ ~~~~~~~~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (C:\Users\ASUS\Desktop\git-practice:String) [Set-Locati
   on], ItemNotFoundException
    + FullyQualifiedErrorId : PathNotFound,Microsoft.PowerShell.Commands.SetLocationCommand

PS C:\Users\ASUS\Desktop> notepad notes.txt
PS C:\Users\ASUS\Desktop> git status
git : The term 'git' is not recognized as the name of a cmdlet, function, script file, or operable pro
gram. Check the spelling of the name, or if a path was included, verify that the path is correct and t
ry again.
At line:1 char:1
+ git status
+ ~~~
    + CategoryInfo          : ObjectNotFound: (git:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\ASUS\Desktop> git add notes.txt
git : The term 'git' is not recognized as the name of a cmdlet, function, script file, or operable pro
gram. Check the spelling of the name, or if a path was included, verify that the path is correct and t
ry again.
At line:1 char:1
+ git add notes.txt
+ ~~~
    + CategoryInfo          : ObjectNotFound: (git:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\ASUS\Desktop> git add notes.txt
git : The term 'git' is not recognized as the name of a cmdlet, function, script file, or operable pro
gram. Check the spelling of the name, or if a path was included, verify that the path is correct and t
ry again.
At line:1 char:1
+ git add notes.txt
+ ~~~
    + CategoryInfo          : ObjectNotFound: (git:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\ASUS\Desktop> git commit -m "Додано файл notes.txt"
git : The term 'git' is not recognized as the name of a cmdlet, function, script file, or operable pro
gram. Check the spelling of the name, or if a path was included, verify that the path is correct and t
ry again.
At line:1 char:1
+ git commit -m "Додано файл notes.txt"
+ ~~~
    + CategoryInfo          : ObjectNotFound: (git:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\ASUS\Desktop> git commit -m "Додано файл notes.txt"
git : The term 'git' is not recognized as the name of a cmdlet, function, script file, or operable pro
gram. Check the spelling of the name, or if a path was included, verify that the path is correct and t
ry again.
At line:1 char:1
+ git commit -m "Додано файл notes.txt"
+ ~~~
    + CategoryInfo          : ObjectNotFound: (git:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\ASUS\Desktop> git commit -m "Додано файл notes.txt"
git : The term 'git' is not recognized as the name of a cmdlet, function, script file, or operable pro
gram. Check the spelling of the name, or if a path was included, verify that the path is correct and t
ry again.
At line:1 char:1
+ git commit -m "Додано файл notes.txt"
+ ~~~
    + CategoryInfo          : ObjectNotFound: (git:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\ASUS\Desktop> git commit -m "Додано файл notes.txt"
git : The term 'git' is not recognized as the name of a cmdlet, function, script file, or operable pro
gram. Check the spelling of the name, or if a path was included, verify that the path is correct and t
ry again.
At line:1 char:1
+ git commit -m "Додано файл notes.txt"
+ ~~~
    + CategoryInfo          : ObjectNotFound: (git:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\ASUS\Desktop> git status
git : The term 'git' is not recognized as the name of a cmdlet, function, script file, or operable pro
gram. Check the spelling of the name, or if a path was included, verify that the path is correct and t
ry again.
At line:1 char:1
+ git status
+ ~~~
    + CategoryInfo          : ObjectNotFound: (git:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\ASUS\Desktop> git add notes.txt
git : The term 'git' is not recognized as the name of a cmdlet, function, script file, or operable pro
gram. Check the spelling of the name, or if a path was included, verify that the path is correct and t
ry again.
At line:1 char:1
+ git add notes.txt
+ ~~~
    + CategoryInfo          : ObjectNotFound: (git:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\ASUS\Desktop> git commit -m "Додано файл notes.txt"
git : The term 'git' is not recognized as the name of a cmdlet, function, script file, or operable pro
gram. Check the spelling of the name, or if a path was included, verify that the path is correct and t
ry again.
At line:1 char:1
+ git commit -m "Додано файл notes.txt"
+ ~~~
    + CategoryInfo          : ObjectNotFound: (git:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\ASUS\Desktop> git push
git : The term 'git' is not recognized as the name of a cmdlet, function, script file, or operable pro
gram. Check the spelling of the name, or if a path was included, verify that the path is correct and t
ry again.
At line:1 char:1
+ git push
+ ~~~
    + CategoryInfo          : ObjectNotFound: (git:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\ASUS\Desktop> git pull
git : The term 'git' is not recognized as the name of a cmdlet, function, script file, or operable pro
gram. Check the spelling of the name, or if a path was included, verify that the path is correct and t
ry again.
At line:1 char:1
+ git pull
+ ~~~
    + CategoryInfo          : ObjectNotFound: (git:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\ASUS\Desktop> git commit -m "Додано файл notes.txt"
git : The term 'git' is not recognized as the name of a cmdlet, function, script file, or operable pro
gram. Check the spelling of the name, or if a path was included, verify that the path is correct and t
ry again.
At line:1 char:1
+ git commit -m "Додано файл notes.txt"
+ ~~~
    + CategoryInfo          : ObjectNotFound: (git:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\ASUS\Desktop> notepad notes.txt
PS C:\Users\ASUS\Desktop> git status
git : The term 'git' is not recognized as the name of a cmdlet, function, script file, or operable pro
gram. Check the spelling of the name, or if a path was included, verify that the path is correct and t
ry again.
At line:1 char:1
+ git status
+ ~~~
    + CategoryInfo          : ObjectNotFound: (git:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\ASUS\Desktop> git add notes.txt
git : The term 'git' is not recognized as the name of a cmdlet, function, script file, or operable pro
gram. Check the spelling of the name, or if a path was included, verify that the path is correct and t
ry again.
At line:1 char:1
+ git add notes.txt
+ ~~~
    + CategoryInfo          : ObjectNotFound: (git:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\ASUS\Desktop> git add notes.txt
git : The term 'git' is not recognized as the name of a cmdlet, function, script file, or operable pro
gram. Check the spelling of the name, or if a path was included, verify that the path is correct and t
ry again.
At line:1 char:1
+ git add notes.txt
+ ~~~
    + CategoryInfo          : ObjectNotFound: (git:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\ASUS\Desktop> git add notes.txt
git : The term 'git' is not recognized as the name of a cmdlet, function, script file, or operable pro
gram. Check the spelling of the name, or if a path was included, verify that the path is correct and t
ry again.
At line:1 char:1
+ git add notes.txt
+ ~~~
    + CategoryInfo          : ObjectNotFound: (git:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\ASUS\Desktop> git commit -m "Додано файл notes.txt"
git : The term 'git' is not recognized as the name of a cmdlet, function, script file, or operable pro
gram. Check the spelling of the name, or if a path was included, verify that the path is correct and t
ry again.
At line:1 char:1
+ git commit -m "Додано файл notes.txt"
+ ~~~
    + CategoryInfo          : ObjectNotFound: (git:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\ASUS\Desktop> git push
git : The term 'git' is not recognized as the name of a cmdlet, function, script file, or operable pro
gram. Check the spelling of the name, or if a path was included, verify that the path is correct and t
ry again.
At line:1 char:1
+ git push
+ ~~~
    + CategoryInfo          : ObjectNotFound: (git:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\ASUS\Desktop>
PS C:\Users\ASUS\Desktop> cd Desktop
cd : Cannot find path 'C:\Users\ASUS\Desktop\Desktop' because it does not exist.
At line:1 char:1
+ cd Desktop
+ ~~~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (C:\Users\ASUS\Desktop\Desktop:String) [Set-Location],
   ItemNotFoundException
    + FullyQualifiedErrorId : PathNotFound,Microsoft.PowerShell.Commands.SetLocationCommand

PS C:\Users\ASUS\Desktop> git clone git@github.com:КабальПавло/git-practice.git
git : The term 'git' is not recognized as the name of a cmdlet, function, script file, or operable pro
gram. Check the spelling of the name, or if a path was included, verify that the path is correct and t
ry again.
At line:1 char:1
+ git clone git@github.com:КабальПавло/git-practice.git
+ ~~~
    + CategoryInfo          : ObjectNotFound: (git:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\ASUS\Desktop> cd Desktop
cd : Cannot find path 'C:\Users\ASUS\Desktop\Desktop' because it does not exist.
At line:1 char:1
+ cd Desktop
+ ~~~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (C:\Users\ASUS\Desktop\Desktop:String) [Set-Location],
   ItemNotFoundException
    + FullyQualifiedErrorId : PathNotFound,Microsoft.PowerShell.Commands.SetLocationCommand

PS C:\Users\ASUS\Desktop> C:\Users\ASUS\Desktop\gstgit clone git@github.com:КабальПавло/git-practice.git
C:\Users\ASUS\Desktop\gstgit : The term 'C:\Users\ASUS\Desktop\gstgit' is not recognized as the name o
f a cmdlet, function, script file, or operable program. Check the spelling of the name, or if a path w
as included, verify that the path is correct and try again.
At line:1 char:1
+ C:\Users\ASUS\Desktop\gstgit clone git@github.com:КабальПавло/git-pra ...
+ ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (C:\Users\ASUS\Desktop\gstgit:String) [], CommandNotFou
   ndException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\ASUS\Desktop> git clone git@github.com:КабальПавло/git-practice.git
git : The term 'git' is not recognized as the name of a cmdlet, function, script file, or operable pro
gram. Check the spelling of the name, or if a path was included, verify that the path is correct and t
ry again.
At line:1 char:1
+ git clone git@github.com:КабальПавло/git-practice.git
+ ~~~
    + CategoryInfo          : ObjectNotFound: (git:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\ASUS\Desktop> cd git-practice
cd : Cannot find path 'C:\Users\ASUS\Desktop\git-practice' because it does not exist.
At line:1 char:1
+ cd git-practice
+ ~~~~~~~~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (C:\Users\ASUS\Desktop\git-practice:String) [Set-Locati
   on], ItemNotFoundException
    + FullyQualifiedErrorId : PathNotFound,Microsoft.PowerShell.Commands.SetLocationCommand

PS C:\Users\ASUS\Desktop> notepad notes.txt
PS C:\Users\ASUS\Desktop> git status
git : The term 'git' is not recognized as the name of a cmdlet, function, script file, or operable pro
gram. Check the spelling of the name, or if a path was included, verify that the path is correct and t
ry again.
At line:1 char:1
+ git status
+ ~~~
    + CategoryInfo          : ObjectNotFound: (git:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\ASUS\Desktop> git add notes.txt
git : The term 'git' is not recognized as the name of a cmdlet, function, script file, or operable pro
gram. Check the spelling of the name, or if a path was included, verify that the path is correct and t
ry again.
At line:1 char:1
+ git add notes.txt
+ ~~~
    + CategoryInfo          : ObjectNotFound: (git:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\ASUS\Desktop> git commit -m "Додано файл notes.txt"
git : The term 'git' is not recognized as the name of a cmdlet, function, script file, or operable pro
gram. Check the spelling of the name, or if a path was included, verify that the path is correct and t
ry again.
At line:1 char:1
+ git commit -m "Додано файл notes.txt"
+ ~~~
    + CategoryInfo          : ObjectNotFound: (git:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\ASUS\Desktop> git push
git : The term 'git' is not recognized as the name of a cmdlet, function, script file, or operable pro
gram. Check the spelling of the name, or if a path was included, verify that the path is correct and t
ry again.
At line:1 char:1
+ git push
+ ~~~
    + CategoryInfo          : ObjectNotFound: (git:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\ASUS\Desktop> git pull
git : The term 'git' is not recognized as the name of a cmdlet, function, script file, or operable pro
gram. Check the spelling of the name, or if a path was included, verify that the path is correct and t
ry again.
At line:1 char:1
+ git pull
+ ~~~
    + CategoryInfo          : ObjectNotFound: (git:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\ASUS\Desktop> git gui &
At line:1 char:9
+ git gui &
+         ~
The ampersand (&) character is not allowed. The & operator is reserved for future use; wrap an ampersa
nd in double quotation marks ("&") to pass it as part of a string.
    + CategoryInfo          : ParserError: (:) [], ParentContainsErrorRecordException
    + FullyQualifiedErrorId : AmpersandNotAllowed

PS C:\Users\ASUS\Desktop> gitk
gitk : The term 'gitk' is not recognized as the name of a cmdlet, function, script file, or operable p
rogram. Check the spelling of the name, or if a path was included, verify that the path is correct and
 try again.
At line:1 char:1
+ gitk
+ ~~~~
    + CategoryInfo          : ObjectNotFound: (gitk:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\ASUS\Desktop> git pull
git : The term 'git' is not recognized as the name of a cmdlet, function, script file, or operable pro
gram. Check the spelling of the name, or if a path was included, verify that the path is correct and t
ry again.
At line:1 char:1
+ git pull
+ ~~~
    + CategoryInfo          : ObjectNotFound: (git:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\ASUS\Desktop> git push
git : The term 'git' is not recognized as the name of a cmdlet, function, script file, or operable pro
gram. Check the spelling of the name, or if a path was included, verify that the path is correct and t
ry again.
At line:1 char:1
+ git push
+ ~~~
    + CategoryInfo          : ObjectNotFound: (git:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\ASUS\Desktop> git pull
git : The term 'git' is not recognized as the name of a cmdlet, function, script file, or operable pro
gram. Check the spelling of the name, or if a path was included, verify that the path is correct and t
ry again.
At line:1 char:1
+ git pull
+ ~~~
    + CategoryInfo          : ObjectNotFound: (git:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\ASUS\Desktop> git push
git : The term 'git' is not recognized as the name of a cmdlet, function, script file, or operable pro
gram. Check the spelling of the name, or if a path was included, verify that the path is correct and t
ry again.
At line:1 char:1
+ git push
+ ~~~
    + CategoryInfo          : ObjectNotFound: (git:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\ASUS\Desktop>
