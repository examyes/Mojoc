<img src="https://github.com/scottcgi/Mojoc/raw/master/Docs/Pic/Logo.png" width="176" height="228" alt="Mojoc Logo" title="Mojoc Logo" />

## Mojoc v0.0.0

Mojoc is open-source, cross-platform, pure C game engine. It is based on **OpenGLES3** and written in C99. It works on IOS and Android currently, but easily extended to other platforms, and will support more platforms in the future.

* Version number v0.0.0 _means =>_ Big Move **.** Function Changes **.** Bug Fix Numbers
 
* Released version will be here [releases](https://github.com/scottcgi/Mojoc/releases).

* Release changes will be here [changelog](https://github.com/scottcgi/Mojoc/blob/master/ChangeLog.md).

* Documents will be here [wiki](https://github.com/scottcgi/Mojoc/wiki).
  * Chinese docs here [中文文档](https://github.com/scottcgi/Mojoc/wiki/%E4%B8%AD%E6%96%87%E6%96%87%E6%A1%A3%E5%88%97%E8%A1%A8).

## Architecture
![Mojoc Engine Architecture](https://github.com/scottcgi/Mojoc/raw/master/Docs/Pic/Architecture.png "Mojoc Engine Architecture")

## License
Mojoc is licensed under the [MIT License](https://github.com/scottcgi/Mojoc/blob/master/LICENSE "Mojoc Under MIT License").

## Core Idea
Less is more, Simple is best, More complex thinking keep less and simple.

## Features

* The only need programming skill is C language with C99.
* In platform-independent code, the C Standard Library is only tool that Mojoc used, in others Mojoc build everything.
* Mojoc has own unique code style. 
  * [Mojoc Code Style](https://github.com/scottcgi/Mojoc/wiki/Code-Style)
* Mojoc use extremely lightweight OOC (Object Oriented C) programing model. 
  * [Mojoc OOC Model](https://github.com/scottcgi/Mojoc/wiki/OOC-(Object-Oriented-C))
* Mojoc application architecture based on Component, State-Machine, Message-Driven. 
  * [Mojoc Component Architecture](https://github.com/scottcgi/Mojoc/wiki/Component-Architecture)
* More feature details see 
  * [Mojoc Main Features](https://github.com/scottcgi/Mojoc/wiki/Main-Features)
    
## Published Games
Mojoc has made a cross-platform android and ios game on the App Store and Google Play. And I will use Mojoc to make more games.
* Super Little Red is bow and arrow shooting game, very challenging your operation.
  * [App Store](https://itunes.apple.com/us/app/id1242353775)
  * [Google Play](https://play.google.com/store/apps/details?id=com.SuperLittleRed)
  * [Tap Tap](https://www.taptap.com/app/45524)

## Samples
The samples are complete, can play, present the Mojoc features game demo. Each platform provides its own platform editor for project build. For example, android use AndroidStudio, ios use XCode, windows use Visual Studio.

Now there is only one sample, which is the simplfied version of published game [Super Little Red](https://github.com/scottcgi/Mojoc/tree/master/Samples/SuperLittleRed).

* #### How to running ?

  * [IOS Folder](https://github.com/scottcgi/Mojoc/tree/master/Samples/SuperLittleRed/IOS) is XCode project that all set up well, just open it with XCode. The only thing need to be set is switch Mojoc platform macro in [Platform.h](https://github.com/scottcgi/Mojoc/blob/master/Engine/Toolkit/Platform/Platform.h).
    ```c
    #define PLATFORM_TARGET PLATFORM_IOS
    ```
  
  * [Android Folder](https://github.com/scottcgi/Mojoc/tree/master/Samples/SuperLittleRed/Android) is AndroidStudio project that all set up well, just open it with AndroidStudio. The only thing need to be set is switch Mojoc platform macro in [Platform.h](https://github.com/scottcgi/Mojoc/blob/master/Engine/Toolkit/Platform/Platform.h).
    ```c
    #define PLATFORM_TARGET PLATFORM_ANDROID
    ```

  * [Code Folder](https://github.com/scottcgi/Mojoc/tree/master/Samples/SuperLittleRed/Code) is sample code shared between android and ios.


## FAQ

* #### Why not C++ ?
  * There are plenty of C++ game engines, but pure C game engines are much rarer. I don't want to repeat, I hope to be differently.
  * The core idea of game engine I want to create is less and simple, which is consistent with the C language.
  * At the beginning, I had a idea of how to build a complex project with pure C language. I want to test the feasibility of the idea, that is Mojoc.
  * The C language is simple but powerful, it can implement a lot of interesting things. **Why not C** ?
    
* #### What is the meaning of Mojoc name ? 
  ```
  Mojoc = Mojo + c
  ```
  The c means the C language.
    
 * #### Who designed the logo and what is the meaning of it ?
   Yes, I designed. The logo is a unknown creature made up of 'Mojoc' letters.
   ```
   M : ears  
   OO: eyes  
   J : body  
   C : tail
   ```
* #### How Mojoc was born ?

  Mojoc started in 2012 as a spare time project. At first, the Mojoc hosted in Google Code website, and use Eclipse + CDT + ADT development, focus on android platform. Everyday after my daytime work, usually at 10 night, I spent one or two hours to develop Mojoc. After 5 years, Mojoc became basically available and developed the first mobile game.
    
  In the time of development, I experienced a lot of repetition and thinking. For a long time, I was not very sure and clear how to use C language to simulate OOP and keep it simple and uniform. So I tried a lot of ideas, repeated the process, write code, modify, refactor, change ideas, delete code, rewrite again and so on.
  
  But in the end, I developed unique rules [Mojoc Code Style](https://github.com/scottcgi/Mojoc/wiki/Code-Style) and [Mojoc OOC Model](https://github.com/scottcgi/Mojoc/wiki/OOC-(Object-Oriented-C)) that make me feel right and great, when follow this rules to develop Mojoc.

  In 2017, through long time hard work, Mojoc becomes a simple, easy and small game engine, and released the first version.

* #### What kind of games Mojoc can do ?
  For now, it is not recommended to use Mojoc make game. Be honest Mojoc is not yet quite perfect. There are many improvements and refinements, and I'm working on it. But now, Mojoc's code architecture and programming model have been established. So Mojoc very suitable for learning and understanding how to use C language to build game engine.
  
* #### What is the future plan about Mojoc ?
  The short term goal is use Mojoc make more games.   
  The long  term goal  is editor, workflow, visual game development.
  
* #### Why developed Mojoc ?
  * It's my coding passion. 
  

## Roadmap
The [Mojoc Roadmap](https://github.com/scottcgi/Mojoc/wiki/Roadmap) gives the direction of the Mojoc development.


## About Me
In short, my programming work started in 2008, and 3 years java server development, 6 years mobile game development. Finally, in 2017, became an independent game developer and created my own game engine Mojoc.


## Support & Donation
  Welcome [fork](https://github.com/scottcgi/Mojoc/issues#fork-destination-box), [issues](https://github.com/scottcgi/Mojoc/issues), star, watch. Any questions, suggestions or ideas, can send mail to me scott.cgi@qq.com. If Mojoc inspired you, valuable to you, if you like it, enjoy it, if you want to support it, you can _=>_ 
  * Play Mojoc [Published Games](#published-games).
  * Donation via [Paypal](https://www.paypal.me/scottcgi/1.28), if buy me a coffee, I will turn the coffee into code.
  
#
_(:loop:) => {_:sunny::coffee::computer::bug::coffee::crescent_moon:_}_
