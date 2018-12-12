CS-352 Project - Logo GUI
=========================

API definition and implemention for using Allegro 5 in CS-352 Project.


## Windows

Build and run using Visual Studio.


## Linux

```sh
g++ -std=c++11 hy352_gui.cpp example.cpp -o hy352_demo $(pkg-config --libs allegro-5 allegro_image-5 allegro_primitives-5 allegro_font-5 allegro_ttf-5)
```


## macOS

#### Terminal

```sh
clang++ -std=c++11 hy352_gui.cpp example.cpp -o hy352_demo -lallegro -lallegro_primitives -lallegro_image -lallegro_ttf -lallegro_font -lallegro_main
```

#### Xcode

Open `./projects/xcode/LogoGUI.xcodeproj`.