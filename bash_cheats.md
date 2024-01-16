[BASH]

CTRL l = Clear terminal
CTRL a = Go to start of line
CTRL e = Go to end of line
ALT  b = Go one word back
ALT  f = Go one word forward
CTRL u = Delete left of cursor
CTRL k = Delete right of cursor
CTRL w = Delete word on left    = ALT backspace
ALT  d = Delete word on right
CTRL y = Paste what was deleted

CTRL / = Undo

[TMUX]

tmux -s <s-name>              = Create tmux session
tmux kill-session -t <s-name> = Kill session
tmux ls                       = list sessions
tmux a -t <s-name>            = list sessions

CTRL b $                      = Rename session
CTRL b d                      = Detach session
CTRL b (                      = Move to previous session
CTRL b )                      = Move to next session

CTRL b %                      = Split horizontal
CTRL b "                      = Split vertical
CTRL b ;                      = Toggle to last active pane
CTRL b <arrow>                = Toggle pane in arrow direction

