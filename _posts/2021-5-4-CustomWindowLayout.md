title: Program concept(part 3)

layout: post

---

## Create custom window layout

- Create TopComponents and arange as you like.  
- Run and close project.
- Create layer.xml and write like this:  
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
- In NetBeans in Files

