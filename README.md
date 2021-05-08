# terminal-go

A minimalistic terminal emulator written in Go 

Playing around with Go's awesome, cross platform GUI kit fyne.io as well interacting with the operation system's (OSX) `pseudoterminal` interface.

~~~bash
# Fetch dependencies
$ go mod tidy

# Run
$ go run .
~~~

This will create a new Window and opens a bash shell (keep in mind... there is no handling for control characters or terminal codes for positioning text!)
