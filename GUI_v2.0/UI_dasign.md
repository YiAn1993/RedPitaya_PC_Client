1. Create/change UI.ui file with qt Designer https://doc.qt.io/qt-5/qtdesigner-manual.html can be insalled with 
```
pip install pyqt5 pyqt5-tools
```
now it can be found someware inside the python installation files named designer.exe

Further information are availible under: 
https://realpython.com/qt-designer-python/#getting-started-with-qt-designer
or
https://www.youtube.com/watch?app=desktop&v=rZcdhles6vQ&list=PLCC34OHNcOtpmCA8s_dpPMvQLyHbvxocY

2. To generate *.py code from the *.ui follow this steps:
    - type into python command promt (not Spyder console)
    ```
    pyuic5 -x <source> -o <output> 
    ```
    where source and output correspond to the filenames including the path, it is also possible to navigate to the folder beforehand
    - The generated file should not be changed, as all changes will be lost if it is generated again.
