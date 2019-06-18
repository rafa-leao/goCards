# goCards

CLI made with the Go standard library to practice flash cards with CSV files.

Inspired by the Quiz App in [gophercises](https://gophercises.com/) and the idea from this repo of [app ideas](https://github.com/florinpop17/app-ideas/blob/master/Projects/FlashCards-App.md)

## How do I use it?

**Be sure you have Go properly installed.**

1. Get the repo:

    - ```go get github.com/rafa-leao/goCards```

2. Check if ```$GOPATH/bin``` is in your path. If so you can use the app anywhere;
    
3. The commands schema:

    - ``` goCards --flag value ```
    - ``` goCards --flag=value ```
    - ``` goCards -flag value ```
    - ``` goCards -flag=value ```
 
4. The command list: 

    - To see the front and back face of your cards: ``` goCards --look file.csv ```      
    - To start practicing with your cards: ``` goCards --play file.csv ```
    
    - And for help: ``` goCards --h --help ```
 
