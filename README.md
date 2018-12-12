HY352 Project - Logo GUI
=========================

API definition and implementation for using Allegro 5 in HY352 Project.


## Windows

Build and run using Visual Studio.


## Linux

```sh
g++ -std=c++11 hy352_gui.cpp example.cpp -o hy352_demo $(pkg-config --libs allegro-5 allegro_image-5 allegro_primitives-5 allegro_font-5 allegro_ttf-5)
```


## macOS

#### Install Homebrew

```sh
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

#### Install Allegro

```sh
brew install allegro
```

#### Compiling from terminal

```sh
clang++ -std=c++11 hy352_gui.cpp example.cpp -o hy352_demo -lallegro -lallegro_primitives -lallegro_image -lallegro_ttf -lallegro_font -lallegro_main
```

#### Using Xcode

Open `./projects/xcode/LogoGUI.xcodeproj`.