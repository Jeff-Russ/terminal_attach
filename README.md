# Terminal Attacher

If you work on OSX in a code editor that lacks a quality built-in terminal and you find that suffling window size and focus between your editor is a workflow killer then this bag of tricks will help.  

This works with any code editor (although defaulted to Sublime Text) together with a program called Moom, an automator file with some Bash and Applescript, and some OSX preference tweeks. This solution will make it so you essentially have the the Mac OSX terminal attached to your code editor With keybord command to resize each pane and toggle focus.

[This video](https://www.youtube.com/watch?v=gq55KoAUsSk) explains a lot.

It also creates right-click and keyboard shortcuts to open any file or folder as a project in your editor, loaded with the terminal pointing to the working directory

## Instructions

1. Install [Moom](https://manytricks.com/moom/) 
2. Drop `com.manytricks.Moom.plist` in `~/Library/Preferences`
3. Launch Moom and in it's prefs > custom make sure you see entries
4. Also make sure it launches upon startup
5. Drop `Open with Sublime` in `~/Library/Services`
6. ⌥⌘⎋ and restart finder
7. Open SystemPrefs > Keyboard > Shortcuts>Services 
8. Look for `Open with Sublime`. Activate
9. Optionally, give it a shortcut. I use ⌃⌥⌘ E

## Usage

When you want to work on a project, right click the folder and 
you'll see and `Open with Sublime` option. If you made a key 
shortcut you can use that instead. 

__key shortcuts to resize:__

⌥ E large __E__ditor on top, small terminal on buttom  
⌥ D medium editor on top, medium terminal on buttom  
⌥ C small editor on top, large terminal (__C__onsole) on buttom







 
