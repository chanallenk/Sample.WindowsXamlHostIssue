# GitRepository
This demonstrates an issue with the WindowsXamlHost and multiple windows when using complex controls in the MainWindow.

To reproduce the issue:

1. Build and launch solution
2. Click the button on the top of the MainWindow to open the ChildWindow on a separate thread
3. Close the ChildWindow
4. Interact with the MainWindow's NavigationView
5. An error will occur
