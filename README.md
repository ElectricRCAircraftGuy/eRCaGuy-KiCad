By Gabriel Staples  
27 Oct. 2018  

# Website:
www.ElectricRCAircraftGuy.com  
- To reach me you can find my email using the "Contact me" link at the top of my website.  

# Project Folders:
* `Libraries` = schematic symbol libraries, PCB layout footprint libraries, etc.
* `Building_Blocks` = standalone circuits, or circuit snippets, which provide modular functionality.
  * Ex: buck converters, boost converters, MOSFET gate drivers, LDO (Low Drop-Out) Linear voltage regulators, etc.
  * These "building blocks" will probably come in the form of standalone KiCad projects.
  * I have found it to be **sooooo hard\*** to learn how to make basic (ie: fundamental and widespread, but not necessarily simple or easy-to-do) building blocks, such as BJT buck converters, N-Ch high-side buck converters, P-Ch high-side buck converters, N-Ch low side buck converters, MOSFET gate drivers using discrete components, etc., that I have finally decided to make this library in order to have a "goto" reference where I can just start pulling schematic blocks for projects whenever I need to make something! 
  * PLEASE FEEL FREE TO CONTRIBUTE YOUR OWN DESIGNS AND BUILDING BLOCKS.

## Justification and rant about my "Building_Blocks" folder:
**\*In my experience talking to other people with engineering degrees,** it seems to me that *most unfortunately*, only 1 out of every 50 or so people with a BS in Electrical Engineering has even the slightest clue how to make their own buck converter, or other, similarly-complex circuit. Of these 1 out of 50 people, 1 out of 5 of them (ie: 1/250 total) knows how to make their own buck converter in more than one way (ex: using a P-Ch high-side MOSFET vs an N-Ch high-side MOSFET vs an N-Ch low-side MOSFET). Of these, 1 out of 5 (1/1250 degreed individuals) can do it in all 3 ways.  

Furthermore, only 1 out of 2 of the 1 out of 50 (1/100 total) "Electrical Engineers", as they call themselves, who *can* make their own buck converter, has the *ability to explain to me* how to do it, and only 1 out of 5 of those 1 out of 2 of those 1 out of 50 (ie: 1/500 total) is *willing to explain to me how to do so*. So, that means 1/2\*1/5\*1/50 = 1/500 "Electrical Engineers" *will* actually teach me how to make a single type of buck converter...and it turns out they are all online and I have yet to meet one in person. If I want to learn how to make all 3 types I've mentioned, only 1/2 *can* explain \* 1/5 *willing* to explain \* 1/1250 can make all 3 types = **1/12500** people will teach me, and they are for sure all online! It is therefore no wonder it is so hard to find someone to teach me these basic things, so I'm going to start documenting it and doing it myself and storing these "Building Blocks" in this library as I go along. I encourage you to contribute and do the same. Let's share the fundamental (both simple *and* complicated) building blocks of electrical engineering with others so that they will no longer be so hard to find and learn. Join me. Let's make this together!

# Donate:
Say "thanks" or give encouragement to continue by donating: https://www.electricrcaircraftguy.com/2016/01/contribute.html.

