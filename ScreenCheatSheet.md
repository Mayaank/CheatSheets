### Screen Cheat Sheet

###### Commands for the terminal
- Use `screen -ls` to get the list of all the open screen session
- `screen -S {name}` initializes a screen with identifier {name}
- `screen -r {name}/{pid}` would reattach the respective screen session in the current terminal


###### Inside the screen session
- Use `(CTRL-a) ?` for help
- `(CTRL-a) "` lists down all the different buffers in the current session of the screen.
- `(CTRL-a) |` and `(CTRL-a) s` splits the screen vertically and horizontally respectively.
- Use `(CTRL-a) <Tab>` for navigating between different views in the current session
- Use `(CTRL-a) c` for opening a new buffer in the current session
- `(CTRL-a) k` kills the current buffer.
- `(CTRL-a) d` detaches the current screen session
