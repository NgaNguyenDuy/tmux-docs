## This repo will be introduce about tmux (terminal multiplexer)

start new:
`tmux`

or start new with a session name:
`tmux new -s session_name`

detach:
`prefix-key d` (my config is C-v d)

List all tmux session:
`tmux ls`

attach session:
`tmux a -t session_name`

kill session:
`tmux kill-session -t session_name`


Inside tmux, press the prefix C-b (default configuration) and then:

### Sessions:
```
:new<CR> new_session_name
s list all session then select a session to attach
$ rename session
```

### Windows:
```
c  create window
w  list windows
n  next window
p  previous window
f  find window
,  name window
&  kill window
```

### Sync Panes
`:setw synchronize-panes`