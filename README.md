# Reproduction repo for shadcn drawer and alert-dialog bug

This bug occurs when using shadcn drawer and alert-dialog together, to reproduce the bug, follow the steps below:
1. Click open to open the drawer,
2. Click open dialog to open the dialog,
3. Click the cancel button in the dialog, which will close the dialog and the drawer at the same time.
4. The scroll behavior of the body is locked due to `overflow: hidden`.
