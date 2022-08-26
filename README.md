### Install xclip to allow copying between system & byobu clipboard 
`sudo apt-get install -yqqq xclip`

### Install byobu
`sudo apt install -y byobu`

### Usefull shortcuts

`shift` + `f1` - help
`ctrl` + `a` `?` - tmux commands 

`ctrl` + `shift` + `f2` - new session
`f2` - new window
`shift` + `f2` - horizontal split
`ctrl` + `f2` - vertical split

`alt` + `up` / `down` - switch session
`alt` + `left` / `right` - switch window
`shift` + `direction` - switch split
`alt` + `shift` + `direction` - resize split

`ctrl` + `f8` - rename session
`f8` - rename window

`ctrl` + `shift` + `f3` / `f4` - move window left / right
`ctrl` + `f3` / `f4` - move split left / right

`shift` + `f8` - toggle split layout
`ctrl` + `d` or `ctrl` + `f6` (for a split running a process)  - kill split one by one

`ctrl` + `a` `k` - kill window
`ctrl` + `a` `\` - kill server
`ctrl` + `a` `d` or `f6` - detach session

`ctrl` + `a` `s` - window / split preview screen

`alt` + `f11` - rips out split into new window
`ctrl` + `f11` - puts window back into split
`shift` + `f11` - zoom in / out of split (zoom in for copying short amount of text without needing to scroll)

`f7` - scroll mode (enter or ctrl + c to exit scroll mode)

to copy large amounts of text - scroll mode and mark text with `space`. pressing `enter` will then copy the text. exit scroll mode with `ctrl` + `c`

can also copy large amounts by enable mouse mode, highlight text then press `enter`.
