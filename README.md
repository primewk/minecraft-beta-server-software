# Minecraft Beta Server JARs 
List of Minecraft Server JARs for Beta Minecraft both Vanilla & CraftBukkit along with few plugins for CraftBukkit.

I don't claim to say these are all the absolute latest releases of their corresponding versions but their close, if you have anything to add to the archive feel free to Pull Request.

I would list em all but theirs honestly so many of them already.

**If you're gonna make a Beta server even just for fun read the important notes below.**

**NOTE**- There is a high chance you're here for b1.7.3 files, if so note that b1.7.3 servers require Java **7** to run, Java 8 will be wonky. To play b1.7.3 on Official Launcher without installing Java 7 will cause crash on launch, to circumvent you can install Java 7 thats annoying. Instead I recommend using PrismLauncher since it automatically installs & runs the correct Minecraft version OR you can run Betacraft.uk's [Betacraft Launcher](https://betacraft.uk/downloads) which runs with a load of fixes for b1.7.3 and few other beta versions.

## Usage
You use beta server JARs like anything other server jar. 
<br>
**Windows**
```bat
@echo off
java -Xms1G -Xmx2G -jar craftbukkit.jar nogui
pause
```
**Linux**
```shell
#!/bin/bash
java -Xms1G -Xmx2G -jar craftbukkit.jar nogui
```

These are generalized examples.

# Notes
1. Most beta servers (esp. pre-1.3) are built for Java 6 or 7.
 - Running them on Java 8+ may cause:
    - `UnsupportedClassVersionError`
    - Handshake crashes
    - Plugin failures
2. Do not allocate TOO much RAM, it can cause Beta servers to break sometimes.

   
