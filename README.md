# Sefaria-Copier
A simple program for copying stuff from Sefaria.org.

# Installation (only works on Windows):

Download [**sefaria_copier_installer.exe**](https://github.com/Whackalenso/Sefaria-Copier/blob/main/sefaria_copier_installer.exe) and run/open it. There's a chance your antivirus might block it, and if so then this won't work. Once you've gone through the steps of the installer, you're done. You can find the app on your desktop, if you search for it in the taskbar, etc.

# How to use

(Because this uses the command prompt, press enter after each step/command)

**1.** Enter the book and chapter for whatever you want to copy from (in the form of book.chapter). The chapter you enter needs to be a number.  
**2.** Enter a section from the book and chapter you selected that you want to copy. These are the different examples for how to specify what text to copy:

```
21-27e
     ^ The language you want (e for English, h for Hebrew)
   ^ Last line of the section
^ First line of the section
```

From a specific line to the end of the chapter: `21-e`  
From the beginning of the chapter to a specific line: `-21e` (`1-21e`
 works too)  

From a specific line in the current chapter to a specific line in another chapter: 
```
21-24.4e
      ^ Last line of the section (for this example, in chapter 24)
   ^ The chapter of the last line in the section
^ First line of the section (in the current chapter)
```
Just one line: `21e`  
The whole chapter: `e`  

**3.** Press enter. This will automatically copy the section to your clipboard, and you will go back to step 2 to keep entering as many new sections as you want. 

Enter "back" to go back to step 1 if you want to change the chapter or book.  
Enter "quit" to quit.



**Btw:**

Since this is uses the command prompt, if you press the up arrow it will type what you typed last. This makes it easier to do certain things.  
You don't need Sefaria.org to be open or even your browser, you just need to be connected to the internet.  
If you get anything that says **Windows protected your PC** during any of this (installation or running the program), click **More info** and then press **Run anyway**.
