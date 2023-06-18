# samp-plugin-xml

![Static Badge](https://img.shields.io/badge/sampctl-samp--plugin--xml-blue)

XML plugin for SA-MP server  
Provides API for parsing XML files  
[Developed by Zeex](https://github.com/Zeex/samp-plugin-xml/)  

Forked repository for compatibility with sampctl

```
~~http://forum.sa-mp.com/showthread.php?t=150755~~  
https://sampforum.blast.hk/showthread.php?tid=150755
```
(Backup of an outdated thread with outdated code. Archive purposes only)

## Installation

Simply install to your project:

```bash
sampctl package install Marevin/samp-plugin-xml
```

Include in your code and begin using the library:

```pawn
#include <xml>
```

## Usage

<!--
Write your code documentation or examples here. If your library is documented in
the source code, direct users there. If not, list your API and describe it well
in this section. If your library is passive and has no API, simply omit this
section.
-->
Native functions are documented in the  ```xml.inc``` file.

Note:  
The following functions are hardcoded to look for files in the ```scriptfiles/``` path.

```
XML_CreateDocument  
XML_LoadDocument  
XML_SetValue
```

## Testing

<!--
Depending on whether your package is tested via in-game "demo tests" or
y_testing unit-tests, you should indicate to readers what to expect below here.
-->

To test, simply run the package:

```bash
sampctl package run
```
