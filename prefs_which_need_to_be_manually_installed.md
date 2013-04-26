# PLUGINS:

* [EGit](http://www.eclipse.org/egit/download/)
* CDT
* [PyDev](http://pydev.org/manual_101_install.html)
* [C/C++ Tests Runner](https://github.com/xgsa/cdt-tests-runner/wiki/Tutorial)
* [Workspace Mechanic](http://code.google.com/a/eclipselabs.org/p/workspacemechanic/)
* [AVR](http://avr-eclipse.sourceforge.net/updatesite)

Things I used to use:
* [Aptana Studio 3](http://www.aptana.com/products/studio3/download)
* No longer using this as I'm starting to prefer the standard colour profile.. 
  but for reference, I used to us: [Color Theme Plugin](http://marketplace.eclipse.org/content/eclipse-color-theme)


# SETTINGS:

* Import the `c++_style_profile.xml` in C/C++ -> Code Style -> Formatter.
* PyDev -> Interpreter - Python -> Forced Builtins -> add "gi"  (this will enable autocompletion for GTK3 stuff)
* PyDev -> Interpreter - Python -> Libraries -> New Folder -> `/usr/local.lib/python2.7/dist-pacakges/pands-0.8.0-py2.7-linux-x86_64.egg`
(it may be a good idea to add many of the folders found with the following simply python script:
```Python
import sys
print sys.path
```
)

## Disable bold text
http://stackoverflow.com/questions/6051980/how-can-i-disable-the-use-of-bold-fonts-when-editing-code-in-eclipse

## When I used to use black background for coding

1. General -> Appearance -> Color Theme -> Wombat
2. (apply the Inactive code highlight AFTER setting and applying Color Theme to Wombat)
3. C/C++ -> Editor -> Inactive code highlight -> #383838
