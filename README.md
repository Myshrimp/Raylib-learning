# Raylib-learning 
1.How to use raylib quickly(only C language available,NOT RECOMMENDED):
Firstly,After downloading raylib,open its file folder,goto raylib/npp, and open notepad for raylib,press F6 to run it.
Secondly,go to raylib/raylib/projects,and select the file with the name of IDE you are using,then you will find a project existing there,open it and you will find a lot of examples in it.You can write your own project on the basis of the current codes now.Of course,you can create a back-up file folder beforehand in case you want to learn from the example codes.
2.How to install raylib in Visual Studio 2022?
  vcpkg solution(Git needed):
  Before doing this,you have to make sure you've installed 'Git',if not,install it first.(Just search 'Git' on browsers and install)
  First step,Make sure your IDE is all English,which means every text shown in the interface must be English,if not,download the English language pack,and don't forget  to rename your file in English.
  Second step,Go to 'View' which you should find on the top left banner,then select 'Terminal',and the following steps are done in the terminal blank.
  Third,type 'git clone https://github.com/Microsoft/vcpkg.git',press Enter key.
  Fourth,type 'cd vcpkg',Enter
  Fifth,type './bootstrap-vcpkg.sh'
  Sixth,type './vcpkg integrate install'
  Seventh,type './vcpkg install raylib',if you are using win64,add ':x64-windows' behind 'raylib'
  (Attention,wait tuntil the process ends after you type every command)
3.Things to be mentioned.
This is a project recording my own process of learning raylib,therefore my solutions on questions I meet may not be viable to anyone else,they are not standard ones.
If you have better ideas and solutions,I would be grateful if you share them with me.Leave a comment if you like!
