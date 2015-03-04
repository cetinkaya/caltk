# caltk
caltk is a simple Tk application that shows monthly calendars. It requires *cal* tool. 

### Example usage

When called without any arguments, it shows the calendar for the current month. You can provide arguments as well. For example, calendar for March 2015 can be seen with:

```
caltk 2015 3
```

or 

```
caltk 3 2015
```

If only one argument is provided it is considered as the month of current year. Since it is March 2015 at the moment, 

```
caltk 3
```

also shows the calendar for March 2015. 

Mouse scroll changes the month and clicking on the caltk window closes the application. 

### Styles

You can choose how caltk looks by providing a style in $HOME/.caltkrc file. Here is an example .caltkrc:

```
bgcolor: #121030
fgcolor: white
todaybgcolor: #121030
todayfgcolor: red
fontsize: 12
padx: 5
pady: 5
geometry: 350x350-0+0
```

This style sets the background of the calendar to the color defined by #121030, and foreground to white. If today is on the calendar shown, it will appear in red color. The font size is set as 12 and paddings for the labels that show days are 5 for both x and y axes. The calendar window size is set as 350 by 350, and the window is placed on the top right corner of the screen.
