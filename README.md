# LeakerSearcher
Quick and simple algorithm to search in local leaks very fast mode
```
                    (                             (                                    
                    )\ )             )            )\ )                     )           
                   (()/(   (    ) ( /(   (  (    (()/(   (    ) (       ( /(   (  (    
                    /(_)) ))\( /( )\()) ))\ )(    /(_)) ))\( /( )(   (  )\()) ))\ )(   
                   (_))  /((_)(_)|(_)\ /((_|()\  (_))  /((_)(_)|()\  )\((_)\ /((_|()\  
                   | |  (_))((_)_| |(_|_))  ((_) / __|(_))((_)_ ((_)((_) |(_|_))  ((_) 
                   | |__/ -_) _` | / // -_)| '_| \__ \/ -_) _` | '_/ _|| ' \/ -_)| '_| 
                   |____\___\__,_|_\_\\___||_|   |___/\___\__,_|_| \__||_||_\___||_|   
 ```
 
# This project is outdated, stay tuned for future updates. Cross-platform support for every operating system will be introduced with the next version of the software (Will be realeased in Java). Also, the next version will support parallel operations to speed up the search. https://github.com/Virgula0/LeakerSearcher2.0

## For what os is developed?
This project is coded in c# so it's made for Windows but you can execute it also on Max Osx downloading Visual Studio for osx from microsoft here:  [Visual Studio](https://www.visualstudio.com/it/vs/visual-studio-mac/)

  ### Prerequisites
  Microsoft .NET Framework (recommended from 3.5 to the latest)

  To run the executable you don't need nothing more...

  ### How it works?
  ```
  ·Verify if your email is in a leak: https://haveibeenpwned.com 
  ·Now download your leak where is your target 
  ·You can use LeakerSearcher to search string in file/s leak/s faster then a manual string recovery. 
  ·Done! 
  ```
  The algorithm of this software is very simple. It is coded to search strings in big files. It's very useful to search in leaks that are some Gbs or more or to search strings in other big files...
  It allows you to choose the best way to search in file/s with an interactive menu.

  ![img](https://i.imgur.com/Au1hLVo.png)

  ### How many Extensions can I scan?

   Available at the moment 
   ```
   .txt .csv .sql
   ```
   
   
    * Option 1 -> (1) Search in a single file. 

     Search for a string in a single txt , sql or cvs file that is very big: 10 gb or more

    * Option 2 -> (2) Search in enumerated files.

    Search for a string in enumerated files from 1.ext to your own n.ext 
    p.s: ext could be .txt .sql or .cvs

    * Option 3 -> (3) Search in all .ext files in a single path.

    Insert you path directory, next the program will scan all files in directory with extension specified by you.
    For example scan all .txt in C:\Users\Desktop\dir to search your own string

    * Option 4 -> (4) Search in all .ext files in a path and its subdirectories.

    Insert you path directory, next the program will scan all files in directory and subdirectory of your path with extension    specified by you.
    For example scan all .txt in C:\Users\Desktop\dir to search your own string
    In the directory there are
     
     --------dir
    |           \
     ------------subdirectory_1 -> search all txt
    |               \
     ----------------subdirectory_2 -> search all txt
     
 
 ### What kind of formatting is supported?
  ```
  email:password
  password:email
  ip:port
  id:email:password
  and similar formatted patterns
  ```
  Instead of ":" there can be other separator like for examples ";" or "\" etc... This is indifferent
  p.s it's not important if password are encrypted or not in search terms.
  
   #### What i have to write to successfully search my interested data?
   Email or Password or Ip or Id to see the entire string with datas.
   Confused strings like: 
   ```
   |-100190209-|-email@example.com-|-Iq8qHA2&£/!WA=-|-username-|--- 
   ```
     ARE NOW SUPPORTED!
 
 ## Graphical Mode
 
 Software ask you for enable a graphical mode while searching.
 
 #### Warning!
 
 If you have a slow pc is recommended don't enable graphical mode to speed up search 
 
 ## Screen
 
 ![img](https://i.imgur.com/9OBUByF.png)
 
 ![img](https://i.imgur.com/Zx5yh17.png)
 
 ![img](https://i.imgur.com/y3OM0F1.png)
 
 ![img](https://i.imgur.com/uKZkbtD.png)
 
 ## Versions (Current: 0.2#Beta)
Added in this version :
The program doesn't stop if string is found but continue search for other strings until it scans all files.
All possible results are printed and are automatically exported to a local directory named 'Results' created at the moment of exportation.
Various adjustaments to the source code.
 
 ## Video
 [![IMAGE ALT TEXT HERE](https://i.imgur.com/ZF6qEy1.jpg)](https://www.youtube.com/watch?v=OXG3YNKDXKE)
 ## Author
 
 Coded by Virgula December 2017 
 https://github.com/Virgula0/LeakerSearcher
 
