# DBGHELPER_ContextMenu
A registry file that adds DBGHELPER to your rightclick context menu

![explorer_m7Voy5RLJ3](https://user-images.githubusercontent.com/45356936/229731198-d0c7cede-aedd-46da-a60a-010ecfd0f80c.gif)


# How to use
You need [DBGHELPER](https://github.com/omicronrex/dbghelper/) first.

1. [Download the reg file.](https://github.com/ohmaytt/DBGHELPER_ContextMenu/releases/download/1.0/dbgcontextmenu.reg)
2. Open the reg file with any text editor.
3. Replace the `<REPLACE THIS WITH YOUR DBGHELPER LOCATION>` with the location of DBGHELPER.
4. Add a single backslash to each backslash, and a single backslash at the end of the path.

![Code_rFL2egPE98](https://user-images.githubusercontent.com/45356936/235910320-1ebf463e-9587-4f5e-84e2-fb7d975736fb.gif)

4. Save the file, then run it.
5. All done!


## Extra : How to add icon
Unfortunately, I do not know how to automate this step. You'll have to manually do this.

1. Open registry editor.
2. Naviate to `Computer\HKEY_CLASSES_ROOT\*\shell\DBGHELPER`
3. Right click on the right side of window, then select `New -> Expandable String Value`
4. Name the new value `Icon`, and double click the value and edit your value data as your DBGHELPER path.
5. It should be done.

<details>
<summary>Click for GIF tutorial</summary>

![regedit_oujx03UY2L](https://user-images.githubusercontent.com/45356936/235911470-ce55f901-8b7c-422e-a0b9-f0c34c060782.gif)

</details>
