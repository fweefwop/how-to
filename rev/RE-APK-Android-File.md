## Reverse Engineering .APK using APKTool-D2J-JDGui

.APK file is the android file format. It can be unpacked by APKTool, reversed by d2j-dex2jar to .class file, then viewed by JD-Gui

### Install APKTool, d2j-dex2jar and JD-Gui
refer to below links for installations:               
[APKTool](https://ibotpeaches.github.io/Apktool/install/)  to unwrapping the package                              
[d2j-dex2jar](https://installlion.com/kali/kali/main/d/dex2jar/install/index.html) to convert unwrapped .dex file to .jar file                
[JDGui](http://java-decompiler.github.io/) to decompile and view the java source code                  

### Steps to RE
1. ```apktool d -s sample.apk```   - this will give you a ```.dex``` file.
2. ```d2j-dex2jar classes.dex```  - this convert ```.dex``` to ```.jar```   
3. ```jd-gui-1.6.6.jar``` - this starts up a GUI so you can view decompiled java code.      



