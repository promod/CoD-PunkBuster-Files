# PunkBuster files for Call of Duty games
Archive of latest PunkBuster files for Call of Duty games.

## Why?

Although contract between Activision and Even Balance has ended and PunkBuster is not supported for Call of Duty games anymore, there is still some useful functionality that PunkBuster can provide for Call of Duty game servers.

One reason is to make obtaining those files easier and second reason is the fear that one day these files will not exist in EvenBalance servers anymore.

## How to use?
Just download the appropriate `pb` folder and move it to the game folder. All missing files will be created from the existing ones. You might need to update your [PBSvc](http://www.evenbalance.com/downloads/pbsvc/pbsvc.exe), though.

## How are files obtained?

Files are obtained using PBSetup tool. Once PBSetup has been run, it creates `pbgame.htm` which contains information about available games in readable format. All one has to do is specify information about missing games.

```
<p> game cod "Call of Duty"
<p> game cod2 "Call of Duty 2"
<p> game cod4 "Call of Duty 4"
<p> game waw "Call of Duty: World at War"

<p> game_os cod w l m
<p> game_os cod2 w l m
<p> game_os cod4 w l m
<p> game_os waw w l m
```

There is a good chance that rerunning PBSetup overwrites this file and as a result deletes the entries above. Making the file write protected for the application can help to combat that.
