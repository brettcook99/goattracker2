# GoatTracker v2.76
## Silver Fork 
##### Macbook related fixes and improvements
\
Editor by Lasse Öörni (loorni@gmail.com)  
HardSID 4U support by Téli Sándor.  
Uses reSID engine by Dag Lem.  
Uses reSID distortion / nonlinearity by Antti Lankila.  
Uses 6510 crossassembler from Exomizer2 beta by Magnus Lind.  
Uses the SDL library.  
GoatTracker icon by Antonio Vera.  
Command quick reference by Simon Bennett.  
Patches and further development by Stefan A. Haubenthal, Valerio Cannone, Raine M. Ekman,
Tero Lindeman, Henrik Paulini and Groepaz.  
Microtonal support by Birgit Jauernig.  
Silver Fork fixes and additions by [Joel Ricci](https://github.com/joelricci).<br>
Undo system by Jason Page.

---
Distributed under GNU General Public License
(see the file COPYING for details)  

Covert BitOps homepage:
http://covertbitops.c64.org  

GoatTracker 2 SourceForge.net page:
http://sourceforge.net/projects/goattracker2  

<br>

-- See **build instructions for  [MAC](../build_instructions_macos.txt)** ! --

<br>

## Revision history

This fork is based on the official above version of Goat Tracker. See [readme.txt](../readme.txt) for full history.

Additional changes in this fork:

- Undo edits using CTRL/CMD+Z (Thanks to Jason Page)
- Toggle ReSID interpolation and filter patch (distortion) mode by clicking INT/FP or press SHIFT+F9.
- Fine vibrato (FV) setting is now saved to config.
- Macbook keyboard insert support using ALT/OPTION+BACKSPACE or FN+SHIFT+BACKSPACE.
- Deleting rows now works correctly on a Macbook keyboard
- Delete using fn + backspace on a Macbook keyboard
- Backspace works as expected when entering filenames
- Better support for some USB keyboards (unwanted characters)
- Build instructions for MacOS (see separate [txt file](../build_instructions_macos.txt))
- Builds on Intel macOS 11 and later
- Resizable window: drag the window edges (or use the green button / ALT+ENTER for fullscreen) and the whole screen scales to fit with sharp text, keeping its proportions.
- Text size: CTRL/CMD + = (bigger), CTRL/CMD + - (smaller), CTRL/CMD + 0 (default size), or A- / A+ in the right-click top bar menu. In fullscreen the screen always fills the display.
- The window size is saved to the config and restored on the next start. The default size fits the desktop.
- Uses the system mouse pointer, so it stays sharp at any size.
- ALT/OPTION+ENTER no longer also enters a keyoff into the pattern.
- MIDI keyboard input (macOS and Windows): notes played on a MIDI keyboard work like the note keys. In the pattern editor they are entered in edit mode and played in jam mode; in the other editors they play the current instrument. Releasing the key releases the note. MIDI note 60 (middle C) is C-4. All MIDI devices and channels are used, and on macOS devices plugged in while the tracker runs are picked up automatically. Turn it off with the `-m0` option or in the config file.
