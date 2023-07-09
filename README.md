# Drawing-Canvas-App

This application has custom drawing widget. We have made the drawing widget with canvas.

The user can draw color, change brush size, change color, erase your drawing, clear screen, undo last action, redo last action, add background from the gallery and save your drawing in the gallery!!!


# Approach:
We just save all paths drawn by the user in an array and to undo, just pop the last saved path from originalPaths list to undoPathlist and call the method invalidate()
