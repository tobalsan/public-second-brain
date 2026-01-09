# TMUX shortcuts cheat sheet

| Action | Shortcut / Command |
| --- | --- |
| Start or recreate a session (detach/reattach) | `tmux` / `tmux new -s name` (detach: `Ctrl-b d`, reattach: `tmux attach`/`tmux a -t name`) |
| Split panes and navigate windows | `Ctrl-b %` / `Ctrl-b "` for splits; `Ctrl-b + arrows` to move; `Ctrl-b c` creates window; `Ctrl-b n`/`p` switch windows |
| Rename the current session | `Ctrl-b : rename-session newname` or `tmux rename-session -t old new` |
| Kill a session | `Ctrl-b : kill-session` or `tmux kill-session -t name` |
| Capture pane output as text | `Ctrl-b : capture-pane -p` (add `> file` or `| tee file`), or `pipe-pane` to stream continuously |
| Send keystrokes into a pane | `Ctrl-b : send-keys 'cmd' Enter` or `tmux send-keys -t session:window.pane 'cmd' Enter` |
| List panes and pane metadata | `Ctrl-b : list-panes` (add `-a` for all) and `Ctrl-b q`; use `#{pane_current_command}`/`#{pane_title}` in formats |
| Set a pane title | `Ctrl-b : select-pane -T codex` or `tmux select-pane -t target -T codex` to change `#{pane_title}` |
