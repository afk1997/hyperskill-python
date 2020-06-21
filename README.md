# [hyperskill-python](https://hyperskill.org/join/bffd9d0ec)
Join JetBrains Academy from [here](https://hyperskill.org/join/bffd9d0ec)

(Under Construction, Updating everday. Do visit again!)

## Projects
- Easy <br />
1. [Zookeeper](https://github.com/afk1997/hyperskill-python/blob/master/README.md#zookeeper)
2. Coffee Machine
3. Credit Calculator
4. Simple Chatty Bot

- Medium <br />
1. Hangman
2. Tic-Tac-Toe
3. Rock-paper-Scissors
4. Numeric Matrix Processor

- Hard <br />
1. Smart Calculator
2. Text-Based Browser
3. Tic-tac-Toe With AI
4. To-Do List

- Challenging
1. Password Hacker
2. HyperCar Service Center
3. HyperJob Agency
4. HyperNews Portal




## [Zookeeper](https://hyperskill.org/projects/98?goal=391)

### About
This short code challenge can help the local zoo look after its denizens. You will create a tool for monitoring animals and their status.
Learning outcomes <br />
This project is aimed at our beginners. It helps you understand some syntax basics and learn how to work with variables, data storage types such as lists, and while loops. <br />
This project is a part of the following track<br /> 
[Python Developer](https://hyperskill.org/onboarding?track=python)

### Stages
- [Stage 1:](https://github.com/afk1997/hyperskill-python/blob/master/README.md#stage-1-rush-into-print)
- [Stage 2:](https://github.com/afk1997/hyperskill-python/blob/master/README.md#stage-2-show-me-an-animal)
- [Stage 3:](https://github.com/afk1997/hyperskill-python/blob/master/README.md#stage-3-whats-inside)
- [Stage 4:](https://github.com/afk1997/hyperskill-python/blob/master/README.md#stage-4-sustainable-care-3)



# Stage 1: Rush into Print
First, let's try to get some simple output from your code.

# Description <br />

There are many animals in the zoo: all of them need care, and some of them are endangered and require preservation efforts. Animals must be fed, cleaned, surrounded by their kin, and kept happy. That is a difficult task for such a big open-range zoo, so one of your employers suggested a better way to accomplish that. She wants to be able to watch any animal on the screen with the help of a special program. <br />
In this project, you will create a program that helps the zookeeper check on the animals and see that they're well. Your product will be able to understand commands from the zoo staff and show the animals on the monitor. <br />

## Objectives
To begin with, you should develop a simple printer. Your program must show the text from the output example. <br />

## Example<br />
Output:<br />
```
I do love animals!
Start looking after animals...
Deer looks fine.
Bat looks happy.
Lion looks healthy.
```
#### [Solution:](https://github.com/afk1997/hyperskill-python/blob/master/Zookeeper/stage1.py) 

# Stage 2: Show me an animal!
Show the zookeeper an image of her ward.

# Description<br />
The important thing about working with animals is watching them. We need to see the animals on the screen to know how they are doing, right? At this time, we are ready to print something awesome: animal images! <br />

## Objectives
In the second stage, you need to develop an animal printer. Your program should show a certain animal: you will find it in the code field. <br />

Please, don't remove the r character at the start of the code template. It's a part of the string and it's important. So, the string should start with r""" sequence. <br />

## Example <br />
Your output should contain the following ASCII image: <br />

```
Switching on camera from habitat with camels...
 ___.-''''-.
/___  @    |
',,,,.     |         _.'''''''._
     '     |        /           \
     |     \    _.-'             \
     |      '.-'                  '-.
     |                               ',
     |                                '',
      ',,-,                           ':;
           ',,| ;,,                 ,' ;;
              ! ; !'',,,',',,,,'!  ;   ;:
             : ;  ! !       ! ! ;  ;   :;
             ; ;   ! !      ! !  ; ;   ;,
            ; ;    ! !     ! !   ; ;
            ; ;    ! !    ! !     ; ;
           ;,,      !,!   !,!     ;,;
           /_I      L_I   L_I     /_I
Yey, our little camel is sunbathing!
```

#### [Solution:](https://github.com/afk1997/hyperskill-python/blob/master/Zookeeper/stage2.py)

# Stage 3: What's Inside?
The zookeeper wants to know what is inside each habitat, by its number.

# Description <br />
The third stage brings new abilities for your software: it will be able to recognize the number of a specific habitat from the input and show the animals living there.<br />

Add all variables with images from the template to a variable with the type list. The order of variables matters: they must be in the order they're defined in the code. The list must contain all of them with no duplicates.<br />

## Objectives <br />
In this stage, your program should: <br />

Ask for a number of the habitat using the following phrase: `Which habitat # do you need?.`<br />
Use the input number as an index of your habitat to print its content.<br />
End with the following phrase:

`The end of the program. To check another habitat restart the watcher please. `
## Examples
The greater-than symbol followed by a space (> ) represents the user input. Notice that it's not part of the input. <br />

### Example 1
```
Which habitat # do you need? > 5
 
Switching on camera from the habitat with rabbits...
         ,
        /|      __
       / |   ,-~ /
      Y :|  //  /
      | jj /( .^
      >-"~"-v"
     /       Y
    jo  o    |
   ( ~T~     j
    >._-' _./
   /   "~"  |
  Y     _,  |
 /| ;-"~ _  l
/ l/ ,-"~    \
\//\/      .- \
 Y        /    Y
 l       I     !
 ]\      _\    /"\
(" ~----( ~   Y.  )
It seems there will be more rabbits soon!

The end of the program. To check another habitat restart the watcher please.
```

### Example 2
```
Which habitat # do you need? > 4
 
Switching on camera from the habitat with bats...
_________________               _________________
 ~-.              \  |\___/|  /              .-~
     ~-.           \ / o o \ /           .-~
        >           \\  W  //           <
       /             /~---~\             \
      /_            |       |            _\
         ~-.        |       |        .-~
            ;        \     /        i
           /___      /\   /\      ___\
                ~-. /  \_/  \ .-~
                   V         V
It looks like this bat is fine.
---
The end of the program. To check another habitat restart the watcher please.
```

#### [Solution](https://github.com/afk1997/hyperskill-python/blob/master/Zookeeper/stage4.py)

# Stage 4: Sustainable Care <3
Finally, your program is able to work for as long as needed!

# Description <br />
It's time to make your project more convenient and understandable. In this final stage, your software will be ready for use by the zoo staff. Your program should understand the habitat numbers, show the animals, and be able to work infinitely. <br />

## Objectives
These are your tasks at this point: <br />

Your program should repeat the behavior from the previous stage, now in a loop <br />
Do not forget to add an exit opportunity for the program: inputting the word exit must terminate the program.<br />
At the end of execution, it must print See you!.<br />

## Example
The greater-than symbol followed by a space (> ) represents the user input. Notice that it's not part of the input. <br />

The complete program should work this way: <br />
```
Which habitat # do you need? > 3
 
Switching on camera from the habitat with a lovely goose...
    
                                    _
                                ,-"" "".
                              ,'  ____  `.
                            ,'  ,'    `.  `._
   (`.         _..--.._   ,'  ,'        \    \
  (`-.\    .-""        ""'   /          (  d _b
 (`._  `-"" ,._             (            `-(   \
 <_  `     (  <`<            \              `-._\
  <`-       (__< <           :
   (__        (_<_<          ;
    `------------------------------------------
This bird stares intently at you... (Maybe it's time to change the channel?)
> Which habitat # do you need? > 1
 
Switching on camera from the habitat with lions...
                                               ,w.
                                             ,YWMMw  ,M  ,
                        _.---.._   __..---._.'MMMMMw,wMWmW,
                   _.-""        '''           YP"WMMMMMMMMMb,
                .-' __.'                   .'     MMMMW^WMMMM;
    _,        .'.-'"; `,       /`     .--""      :MMM[==MWMW^;
 ,mM^"     ,-'.'   /   ;      ;      /   ,       MMMMb_wMW"  @\
,MM:.    .'.-'   .'     ;     `\    ;     `,     MMMMMMMW `"=./`-,
WMMm__,-'.'     /      _.\      F'''-+,,   ;_,_.dMMMMMMMM[,_ / `=_}
"^MP__.-'    ,-' _.--""   `-,   ;       \  ; ;MMMMMMMMMMW^``; __|
           /   .'            ; ;         )  )`{  \ `"^W^`,   \  :
          /  .'             /  (       .'  /     Ww._     `.  `"
         /  Y,              `,  `-,=,_{   ;      MMMP`""-,  `-._.-,
        (--, )                `,_ / `) \/"")      ^"      `-, -;"\:
The lion is croaking!
Which habitat # do you need? > exit
See you!
```

#### [Solution](https://github.com/afk1997/hyperskill-python/blob/master/Zookeeper/stage4.py)



