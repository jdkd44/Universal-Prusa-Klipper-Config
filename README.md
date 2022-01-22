*This is a work in progress for the time being. So until this message is deleted, expect things to not work*

# Universal Prusa Klipper Config

**Before you use this configuration, make sure you read this readme!!**

Yes, this is another klipper config for the Prusa MK3S/S+. What makes this different than the others? It is simple. Thats it. 

A lot of other configs have a bunch of "features" that are great, but for a beginner in the world of Klipper, it is confusing and may create issues that one would not have on a clean klipper config. I will try to solve this, and also give you the user the flexibility for the future when you decide to customize the config.

## What this config has
This configuration has all of the basics enabled so that one could load up this configuration after editing it to their printer's configuration and hit print.

## What this config does not have
Any shiny features enabled like steel sheet switching, complex macros, or any other features that would confuse you. If you are an experienced klipper user then feel free to start enabling these features.

## How to get this config working with your printer
1. Open up ``printer.cfg`` in your favorite code editor and start looking at all of the standard settings you need to enable or disable. Comment or uncomment the lines using a ``#`` symbol to enable or disable a line. **Warning: In some areas you can only have one configuration file uncommented. You will be notified when this is the case in the file.**

2. After the changes are made, copy all of the files and folders in this repo into your klipper config folder on the pi. 

3. Command a ``firmware_restart`` in the klipper terminal to have the config loaded and get ready to debug. Google and looking into the config is your best friend.



