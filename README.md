# JC2-MP Waypath Builder
![Screenshot](https://raw.github.com/awestroke/jcmp-waypathbuilder/master/screenshot.png "Screenshot of Waypath Builder in action")

A Just Cause 2: MP development tool for creating and exporting series of waypoints. 

Use to:
* Create racing tracks
* Create spawn locations for your game mode
* Record positions with ease

## Installing
```git clone``` the repository in the scripts folder of your server. 

See the [JC-MP Server documentation](http://wiki.jc-mp.com/Server) for how to use scripts.

## Upgrading
```git pull``` in scripts/jcmp-waypathbuilder

## Usage
**target** is the closest waypoint. It will be highlighted in green.
* ```/wpb add``` or ```<NumPadPlus>```: Add a waypoint
* ```/wpb del``` or ```<NumPadMinus>```: Remove target
* ```/wpb save [prefix]```: Save waypoints
* ```/wpb clear```: Clear all waypoints
* ```/wpb move +``` or ```<NumPadMultiply>```: Reorder target (+1)
* ```/wpb move -``` or ```<NumPadDivide>```: Reorder target (-1)
* ```/wpb move <n>```: Reorder target (=n)

Files are saved as &lt;timestamp&gt;.json in the Waypath Builder script folder. 
If a prefix is supplied, the file is saved as &lt;prefix&gt;_&lt;timestamp&gt;.json


## Contributing
* All improvements are very welcome
* Test everything before you submit a pull request
* Adapt to the indentation used
