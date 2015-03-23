Comment #1
(Running on iPhone 5s emulator)

The App Itself:
The app itself does not run. It can be fixed by setting win1 by itself at the very beginning, instead of declaring a function and set win1 inside of it. 

Navigation:
There is no navigation of any sort. There should be some kind of navigation, e.g. tabs, buttons, etc.

Tea Selection:
The only thing that worked was the table view of the tea colors. Once I click on a color, an error appears, “undefined is not a function (evaluating ‘colour.chartAt (1)’)”. The function is not working because there is not a function created, instead, only the structure of the function was. This can be fixed by declaring a function, and include all codes for it inside, then call the function to run. 

Camera:
There is a repeated code making a window called win1. It should be called another name, because the camera function is going to be in another window.
