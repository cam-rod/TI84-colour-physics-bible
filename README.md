# The TI-84 Colour Edition Physics Bible Program

This is a program designed for the **TI-84 Plus Colour Edition (TI-84+CE)**  and the **TI-84 Plus C Silver Edition (TI-84+C SE)**, to help you solve for different key values needed in a variety of physics equations. The equations calculated in the program are derivations of the 5 equations of uniformly accelerated motion in one dimension, which can be viewed [here](https://i.imgur.com/5MSZ8Nv.jpg). This program can solve for any of the following variables if 3 others are known (measurement units in parentheses):

- Acceleration (in m/s²)
- Displacement (in m)
- Initial velocity (in m/s)
- Final velocity (in m/s)
- Time (in s)

This program is written in TI-BASIC, and will work from RAM or the Archive. Due to the size of the program (12 119 bytes on TI-84+CE, 13 491 bytes on TI-84+C SE) without the automatically generated list ```PHVAR```, it is recommended to store the program in the Archive. Although this program is capable of running on black and white display TI-83/84 graphing calculator, it is *not recommended*, as the text is optimized for the larger colour displays and will wrap on top of itself on black and white screens.

## The Physics Bible in Action

![Launch Splash Screen](https://i.imgur.com/1qUCiJA.png) ![Main Menu Instructions](https://i.imgur.com/9OXL4Ku.png) ![Main Menu](https://i.imgur.com/bp2uc9T.png) ![Sub Menu](https://i.imgur.com/XK1S3Ob.png) ![Calculation Screen](https://i.imgur.com/C5ShIpO.png) ![Saving Answer](https://i.imgur.com/pbN3QPW.png) ![Answer Saved in Variable](https://i.imgur.com/QJ0WbJn.png)

## Installing the Physics Bible

To download the program, follow [this link](https://github.com/cam-rod/TI84-colour-physics-bible/releases) and select the version for your calculator Then, head over to the download site for the [TI Connect CE software](https://education.ti.com/en/products/computer-software/ti-connect-ce-sw) and follow the instructions in the guidebook to send the program to your TI-84+CE. Finally, to run the program, press the ```pgrm``` button, and then select the program called ```PHYSBBLE```.

## Building the Physics Bible

If you wish to build the program yourself from the text files attached, follow the instructions below. Due to the formatting of the text, the program must be compiled with [TI Connect CE](https://education.ti.com/en/products/computer-software/ti-connect-ce-sw), but feel free to reformat for the IDE of your choice:

1. Download and extract the ```.zip``` file from the button above or with [this link](https://github.com/cam-rod/TI84-colour-physics-bible/archive/master.zip).
2. Open the corresponding folder and the file ```PHYSBBLE-TI-84-XXXXXX.txt```. Copy all of the text in the file.
3. Open *TI Connect CE* and create a new program under the *Program Editor Menu*. Paste the text in the empty space. Give the program a variable name and save the file. Follow the installation instructions [above](https://github.com/cam-rod/TI84-colour-physics-bible#installing-the-physics-bible) to send the program to your calculator.

## Contributing

If you would like to contribute, please follow the guidelines below:

- All pull requests should be rebased onto the latest release version on the master branch first.
- Test your changes **and** general functionality on a TI-84+CE before submitting a pull request.
- Bug reports should include as much detail as possible; move the program into RAM and use ```Goto``` on the error page to provide context.

## License

This software is licensed under the MIT License, which can be found [here](LICENSE), or the online template [here](https://opensource.org/licenses/MIT). If you use this repository in other projects, include the aforementioned license, with attribution to myself.
