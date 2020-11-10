# Lab 1 Description

First, You'll need to install:</br>

1. The Visual Studio Code [Code Runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner)
2. The Microsoft C/C++ extension for VS Code [C/C++ Extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools)

***

For the [Simple Lexical Analyzer](lab1/simple_lexical_analyzer):
</br>

We first define our phrase at [Phrase](lab1/simple_lexical_analyzer/lexicalanalyzer.cpp) and then run [Cpp File](../lab1/simple_lexical_analyzer/lexicalanalyzer.cpp)

For an example phrase like: </br> int a,b,c; </br> a=12-(c*b+2);

We'll get an output like below:</br>

![Simple_lexical_analyzer.png](screenshots/simple_lexical_analyzer.png")

***

For the [Bonus Flex Analyzer](lab1/bonus_flex_analyzer):
</br>

We first install:

1. Fast Lexical Analyser Generator from [Flex](https://sourceforge.net/projects/gnuwin32/files/flex/2.5.4a-1/flex-2.5.4a-1.exe/download?use_mirror=liquidtelecom&download=)

2. MinGW which is a native Windows port of the GNU Compiler Collection (GCC) from [MinGW](https://osdn.net/projects/mingw/releases/)

Then we navigate to [Bonus Flex Analyzer](lab1/bonus_flex_analyzer) folder our command prompt and enter:

1. flex lexicalanalyzer.l

2. gcc lex.yy.c

In the exe file that's generated, we enter our phrase and press enter

We'll get an output like below:</br>
    ![Bonus_flex_analyzer.png](screenshots/bonus_flex_analyzer.png")
