# Arcade: 1943 for MiSTer

*JT_GNG FPGA Clone of Ghosts'n Goblins by Jose Tejada (@topapate)*

JT1943 FPGA clone of 1943 arcade faithful to original hardware
==============================================================

Please, read the main README file too.

You have just got an expensive $500 PCB according to eBay. You have in your hands
a faithful conversion of the circuits on the 1943 PCB to FPGA. If you come from
the emulation world here are some of the things different from emulators:

-Real CPU/GPU bus sharing with delays
-Sprites handled with DMA exactly as in the original hardware
-Palettes determined by the original PROMs
-Graphics priority handled by the original PROM
-No lag between image and input. Data is being sent to the screen in real time.
-3 button input (although the game seems to use only two buttons)
-Sound sampling rate: 41.663 kHz (original, 125/3 kHz)

These technical aspects mean that the game play will be different from an emulator
in a number of ways and that some hardware tricks that were not emulated will work
here as in the original hardware.

*Original repository: http://github.com/jotego/jt_gng*

## Installation
Copy the `*.rbf` and `a.1943.rom` into the root folder of the SD card.

## Keyboard inputs
| Key | Function |
| --- | --- |
| F1 | Start 1 player |
| F2 | Start 2 players |
| F3 | Add Coin |
| F4 | Pause |
| F5 | Test Switch |
| SPACE | Jump |
| CTRL,ALT | Fire |
| UP,DOWN,LEFT,RIGHT | Movements |

Joystick support

 - *Note1: in continue screen use combo Fire + 1P/2P to continue*

## Building ROM 
### :rotating_light: :rotating_light: :rotating_light: Attention!! :rotating_light: :rotating_light: :rotating_light:
ROM is not included. In order to use this arcade, you need to provide a correct ROM file.
1) Put bat and 7za.exe files from releases folder into the same folder on PC.
2) Execute bat file - it will show the name of zip file containing required files.
3) Find this zip file somewhere. You need to find the file exactly as required.
   Do not rename other zip files even if they also replresent the same game - they are not compatible!
   The name of zip is taken from M.A.M.E. project, so you can get more info about
   hashes and contained files there.
4) Put required zip into the same folder and execute the bat again.
5) If everything will go without errors or warnings, then you will get the rom file.
6) Place the rom file into root of SD card.

## GAME PLAY

It is obvious what you have to do except:

-Press fire 1 and 2 to roll
-Hold the coin button during power up to test mode in order to be
 able to access al test options
-Hold fire 1 at the end of an air carrier phase to receive a weapon at the
 beginning of the next phase

## CREDITS

Brought to you by Jose Tejada, aka jotego. Meet me in twitter @topapate
Checkout my patreon page here: http://patreon.com/topapate

Special thanks to all March '19 patrons.

### Tier +3 Patrons Thanks!!

Alan Steremberg
albconde
Andrew Moore
Andyways
Blue1597
Brian Sallee
Bruno Silva
Carl Hagström
Carlos Del Alamo
Christian Bailey
crashman
Dag J.
Daniel Hochman
DarkStar7
Darren Newman
Dave Ross
Diego Losada Somoza
Don Gafford
Duane Hembrick
Dustin Hubbard
Ed Balan
Eoin Gibney
Fay Dek
Filip Kindt
Frank Wolf
Fred Fryolator
Fredrik Berglind
Funkycochise
furrtek
Geert Oost 
Gonzalo López
Gregory Hogan
Gus Marruedo
Jacob Proctor
James DeRose
Jan Beta
Javier Martínez
JD
Jeremy Glass
Jérôme Moreau
Joe Kalwitz
Johannes Reß
John Klimek
Joshua Witt
Jo Tomiyori
Keith Kelly
Kevin Bidwell
Leslie Law
loloC2C
Mads Troest
Mahen
Manuel
Manuel Antoni
Manuel Astudillo
Manuel Fernández
Manuelfx
Marcos
Marco Tavian
Mark Kohler (NML32)
Mary Marshall
Matt Charlesworth
Matthew Coyne
Matthew Langtry
Michael Stegen
Michael's Workshop
Michael Troelsen
Miguel Angel Rodriguez Jodar
Mike Holzinger
Name
Neil Maguire
Nicolas Hamel
Obiwantje
Oliver Jaksch
Oliver Wndmth
Oscar Laguna Garcia
Oscar López Sierra
Owlnonymous
Peter Edwards
Phillip McMahon
Popov
Porkchop Express
PsyFX
QcRetro
remowilliams
RetroShop.pt
Rinpoe
robert fisher
Rob Young
Roland
Rysha
Salvador Perugorria Lorente
Scott Redepenning
Scralings
SJohansson
SmokeMonster
StalkS
Stephen Marshall
Stephen Nuthall
Suvodip Mitra
Thomas Tahsin-Bey
Tommaso Mauro Tautonico
Travis Brown
type78
Ultrarobotninja
Víctor Gomariz Ladrón de Guevara
Violeta Martin Fernandez
Vorvek

