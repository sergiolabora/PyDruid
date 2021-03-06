<div align="center">
    <img src="assets/pdlogo.svg" title="Druid" width=70%>
</div>

<div align="center">
    <img src="https://img.shields.io/github/last-commit/sergiolabora/PyDruid?label=Last%20Commit"/>
    <img src="https://img.shields.io/github/commit-activity/m/sergiolabora/PyDruid?label=Activity" />
    <img src="https://img.shields.io/github/downloads/sergiolabora/PyDruid/total?label=Downloads" />
    <img src="https://img.shields.io/github/stars/sergiolabora/PyDruid?label=Stars&logo=github" />
    <img src="https://img.shields.io/github/languages/code-size/sergiolabora/PyDruid?label=Code%20Size" />
</div>

# The PyDruid compiler

<div align="center">
    <img src="assets/terminal.png", title="Druid Example" width=90%>
</div>

PyDruid is the first ever Druid compiler that I wrote. It's basically meant to compile the actual Druid compiler in written in Druid, which is compiled to machine code rather than being a bunch of Python scripts.

## ![](assets/warning.svg) __Warning__
This repository is still under development and __won't__ work in any way.

## ![](assets/worm.svg) What's Druid?
Druid is a strong-typed object-oriented programming language. It's a mix of my favourite features of my favourite programming languages (Python, Java, C, etc...) that compiles into C to be later compiled to machine code.

## ![](assets/worm.svg) Why PyDruid?
Well... the Druid source code is being written in Druid (as paradoxically as it might sound), so a single C compiler cannot compile the Druid source code. There must be a _primitive_ Druid compiler in order to compile the actual Druid repository. PyDruid is meant to be this compiler, which can be run using Python on any computer to compile the compiler.

## ![](assets/worm.svg) Install
Simply you don't install it. You need just a requeriment to run it, which is Python (and preferably running on Linux). The compiler is called by running the file ```druidc```, in the root directory of the git repository.

## ![](assets/worm.svg) Compile
Druid doesn't compile single Druid files. You need to pass a project name to the compiler, and it will look for a project index wich will tell the project name, the project author, the project files, the compiler and its flags, etc...
```
$ ./druidc compile example.druid
```

## ![](assets/worm.svg) Other options
The compiler can do more things, such as initializing projects, for example. It basically does everything that the actual Druid compiler does, so if you want to get a list with all the available options, just use the option ```help``` or check the [options.md](docs/options.md) file.

## ![](assets/worm.svg) License
This software is released under the CC BY-NC-SA license, which allows you to modify and share my work, as long as you give attribution to me and don't earn any money from this work. However, if you made a program using Druid, you're free to do whatever you want with your program. If you want to read the license, check the [LICENSE.md](LICENSE.md) file.

<div align="center">
    <img src="assets/by-nc-sa.svg" width=30% title="CC BY-NC-SA" href="https://creativecommons.org/licenses/by-nc-sa/3.0/es/" title="View CC BY-NC-SA license on creativecommons.org">
</div>
