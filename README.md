# CSS-Organizer
CSS-Organizer is a organization script used for organizing CSS files based on a variety of commonly used conventions such as block, properties and alphabetical order.
CSS-Organizer is fully customizable with a wide variety of options such as indenting, minmizing files, and can be easily be implemented as a script for any website.

Customization is done with a text file called **Options.txt** which can be generated and saved. For a more detailed guide on how to use **Options.txt** look below.

### Python (Recommended)
CSS-Organizer can also be ran locally using Python **(3.0+)**. CSS-Orgganizer should be ran via using a Python IDE or using the cmd line. CSS-Organizer will check the local location of the script, i.e. the one in the folder where you first installed it.
Please note you must **MANUALLY** change the default.txt this way, or generate one using [CSS Organizer](johnsong.science/projects/css_organizer#generator "CSS Oragnizer Options.txt")

# Installation
CSS-Organizer is made using (**Python 3.0 +**) and can be installed by calling. Calling cssorg on a dir will
by default, organize all files within that directory (**does not check sub-directories**).

> $ python setup.py install

> $ cssorg dirname a

# Default Settings
By default CSS-Organizer organizes it by blocks as the following

1. Position
2. Display 
3. Font
4. Colour
5. Animation
6. Misc

All these blocks are organized with a inner text file which is editable called default.txt, which takes into account how many blocks there and how specific properties within these blocks are organized. The text file controls the placement and the values of the above rules, e.g. a general convention is that the rule **Width** before **Height** in the display block, all other unknown properties are sorted by alphabetical order.

# Complete options

Below are the options along with their default values

- RECURSIVE: False
- ORDER: (default) Block / Length/ Random/ Alpha
- BLOCKTABS:True
- ORDER-BY-NAME:True
- DYNAMIC-TABBING:True

For a complete list of options please visit [CSS-Organizer API](johnsong.me/projects/CSS_Organizer, "CSS-Organizer API")
