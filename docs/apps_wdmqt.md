# Wisdom
A beautiful and user-friendly GUI Wikipedia application

[Find the repository here](https://github.com/t0xic0der/wisdom)

<p align="center">
    <img src="https://img.shields.io/github/issues/t0xic0der/pharmadb-store?style=flat-square&logo=appveyor&color=teal">
    <img src="https://img.shields.io/github/forks/t0xic0der/pharmadb-store?style=flat-square&logo=appveyor&color=teal">
    <img src="https://img.shields.io/github/stars/t0xic0der/pharmadb-store?style=flat-square&logo=appveyor&color=teal">
    <img src="https://img.shields.io/github/license/t0xic0der/pharmadb-store?style=flat-square&logo=appveyor&color=teal">
</p>

## Requirements
1. PyQt 5
2. Wikipedia for Python
3. Qt Designer
4. Any code editor
5. Active internet connection

## Introduction
This is a simple, beautiful and user-friendly GUI Wikipedia application which takes the search request that you are interested in to find information about it from Wikipedia.

## Features
At this point of time, only a limited set of features work with an unreasonably high (but tolerable) waiting period.

1. Main content of the article
2. Summary of the article
3. Suggested articles for the request
4. Related articles for the request
5. References used for the article
6. Image sources used for the article
7. Donate to Wikipedia
8. Documentation of the API

## Bugs/Drawbacks
1. **Unreasonably high wait time** - Keeping in mind how famous Wikipedia is and the number of requests it needs to address per minute, this drawback is not likely going to be fixed any time soon.
2. **Unresolved exception** - Some search requests result in unresolved exception which are handled generally but a workaround is yet to be provided to the user.
3. **Search dependence** - The request for the list of related articles, references and image sources run the search based on the present keyword in the search bar.
4. **Messed up fontfaces** - At some places, paddings and margins need to be provided judiciously in order to make sure that suspended and headed regions are visible.

## Screenshots

### Testing Default
![Default Screen](pics/apps/wdmqt/sdefault.png)

### Testing Tom Clancy's Ghost Recon Breakpoint
![Breakpoint Screen](pics/apps/wdmqt/brekpint.png)
