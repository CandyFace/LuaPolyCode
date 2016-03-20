# LuaPolyCode
Syntax highlight and code completion for [Polycode](http://Polycode.org) lua scripting in Sublime Text 3

### Features:
- Syntax Highlight
- Code Completion
- Build and run directly from sublime-text
- .polyproject template via command-palette

### Snippets
![Snippit of syntax highlight](http://i.imgbox.com/fBsoGP0i.png)
![Snippet of code completion](https://zippy.gfycat.com/SplendidTepidHookersealion.gif)
![Snippit of build and run](https://zippy.gfycat.com/ReadyEarnestAmericancreamdraft.gif)

TODO:
 - [x] Syntax highlighing
 - [x] Build/run System
 - [ ] Smarter code completion
 - [x] 2D Physics related code completion
 - [x] 3D Physics related code completion
 - [x] Project generation snippet
 - [ ] CORE functions related code completion
 - [ ] Cleanup syntax in sublime.syntax, because setup originally from Erlang template.
 
### How to install:
`Currently the package is not available in Package control. Therefore to install manually:`

go to `Preferences -> Browse Packages.` 
Download and unzip this package into that directory, or:
`git clone https://github.com/CandyFace/LuaPolyCode.git "LuaPolyCode"`

### How to build and run (Presumably only works for OSX)
#### Setup your PATH 
First you have to add `polybuild to your PATH`, else sublime won't build.

There are mutiple ways to setup PATH, I used `cp` and send `polybuild` to `/usr/bin`

polybuild is located in /Polycode/Release/Darwin/Standalone/Bin

#### Setup project 
The build system is dependant on `.sublime-project` therefore you have to add the project folder to sublime text, and save it.

------------------------------
After you've setup your PATH and the project structure, you should be able to build and run via sublime's command palette or via Tools->Build System->LuaPolyCode


