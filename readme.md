Refactoring Golf
================
Provides Java Sources for the game 'Refactoring Golf'

Getting Started
---------------
- check it out: `git clone https://github.com/plipp/Refactoring-Golf.git`
- import the maven-poms of the Course, you want to play (1. First Course , 2. Second Course ...), into your favorite IDE
- start playing according to the following rules

###The rules

Compare the directories with the code of the single golf holes and try to do the refactorings required to get 
from one hole to the next: E.g. compare<br>
```  
  0. Initial Tee/src/main/java/refactoringgolf/store
  <-->
  1. First Hole/src/main/java/refactoringgolf/store
```  
and start refactoring.

For each refactoring the following (minus-)scores have to be summed up:

**Normal Points**

- 1+1 Cut&Paste
- 1 Shortcut for Refactoring-Method
- 0 Formatting

**Strafpunkte**

- 2 edit a word manually
- 2 if code doesn't compile after a refactoring

The team with the minimum (minus-)score wins at the end.


Learning Support
================

IntelliJ Idea
-------------
- Keymap (adapted to OS, *Help->Default Keymap Reference*)
    - Power-Shortcuts: 
        - 'Find Action' (Default: *CTRL+SHIFT+a*)
        - 'Search everywhere' (Default: *SHIFT+SHIFT*)
        - 'Show intention actions and quick-fixes' (Default: *ALT+ENTER*)
- Plugins:
    - [Key Promoter] (https://plugins.jetbrains.com/plugin/1003)
    - [IntelliJ Code Golf] (https://plugins.jetbrains.com/plugin/7243)
    - [Presentation Assistent](http://plugins.jetbrains.com/plugin/7345?pr=idea), [more details ...](http://blog.jetbrains.com/idea/2014/09/touring-plugins-presentation-assist/)


Last but not Least...
=====================
Many thanks for this inspiration to [snahider] (https://github.com/snahider/Refactoring-Golf.git)
