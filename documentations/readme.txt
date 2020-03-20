Multiple Document Interface
1.Create .Net container with System.Windows.Form.Panel.
2.Create child window-Get window handler of Parent and child,Set Parent (FindWindowA,Set        parent User32.dll)
Set Front Panel bounds.
3.Remove child window-Detach it from parent and close reference
4.Dock,Undock-Detach child window from parent (SetParent call library function-ParentHWND=0)
5.VI activation,VI Deactivation event case to generate VI name of active child window
6.Tile and Cascade -user32.dll:TileChildWindows,user32.dll:CascadeChildWindows
7.Close Application-Detach all child windows from parent and close all references.

To Do:
1.How to load and display VIs with the same name.
2.Whether to set position within API or by user.
