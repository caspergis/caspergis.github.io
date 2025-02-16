---
title: Create custom window

layout: post
---


## Create custom window layout

- Create TopComponents and arange as you like.  
- Run and close project.
- Create layer.xml and write like this:  
    [Layers.xml](https://github.com/bpodolski/CasperGIS/blob/master/Core/src/io/github/bpodolski/caspergis/layer.xml)  

```xml
<filesystem>
    <folder name="Windows2">
        <file name="WindowManager.wswmgr" url="gui/modes/WindowManager.wswmgr"/>
        
        <folder name="Modes">
            <folder name="explorer">
                <file name="ProjectListTopComponent.wstcref_hidden"/>
                <file name="InactiveMapLayersTopComponent.wstcref_hidden"/>
            </folder>
            <folder name="output">
                <file name="BookmarksTopComponent.wstcref_hidden"/>
            </folder>
            <file name="ProjectListMode.wsmode" url="gui/modes/ProjectListMode.wsmode"/>
            <folder name="ProjectListMode">
                <file name="ProjectListTopComponent.wstcref" url="gui/modes/ProjectListTopComponent.wstcref"/>
                <file name="InactiveMapLayersTopComponent.wstcref" url="gui/modes/InactiveMapLayersTopComponent.wstcref"/>
            </folder>
            <file name="BookmarksMode.wsmode" url="gui/modes/BookmarksMode.wsmode"/>
            <folder name="BookmarksMode">
                <file name="BookmarksTopComponent.wstcref" url="gui/modes/BookmarksTopComponent.wstcref"/>
            </folder>
        </folder>
    </folder>
</filesystem>
```

- in package you like, create files:
1. *WindowManager.wswmgr* - a file describing the general properties of the window manager (in ot i we define, for example, the size of icons in the toolbar)
2. *[1,2,...].wsmode* - files describing the parameters of a given place(mode) in the application
- In NetBeans in Files find directory: [Project]\build\testuserdir\config\Windows2Local\.   

open WindowManager.wswmgr and copy the contents to your own file.
Content of the modes files you can find in direciories named like *"AcstractMode_1"*.

