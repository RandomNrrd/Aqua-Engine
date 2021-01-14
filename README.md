# Aqua Engine
## Configuration
To configure Aqua Engine click on the Engine Folder and open the main.py file this will configure the engine onto your machine. To get started open Filemanager.py. Filemanager.py will create a file name file.py. Rename this file and then ight click and press edit. To Debug code click main.py to open up the main scene.
## Minimum Requirments
OS: Windows Xp
Processor: Dual Core 2.0 Ghz
Memory: 2GB
Hard Disk Space: 200MB
Video Card: 128mb Video Memory
## Usage

Below is another example of displaying
````python
import csv

with open("sample.csv","r") as csvinput: # read input csv file
    reader = csv.reader(csvinput) # create a reader
    for row in reader:
        print(row[0])
````
