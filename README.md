# pi4j-core-osgi
This repository contains a bundle with the following line added to `MANIFEST.MF` to use the I2C function of [Pi4J 1.2 (pi4j-core.jar)](https://pi4j.com/download/pi4j-1.2.zip) in Java8 / OSGi environment.
```
Import-Package: sun.misc;resolution:=optional
```
**Note. To use Pi4J 1.2's I2C functionality, sun.misc.SharedSecrets.class is required, but this class can only be used up to Java8 and cannot be used since Java9.**

I would like to thank the authors of this very useful Pi4J code, and all the contributors.
