** Surround

`cs"'` replaces `"` for `'`.
`ds'` removes `'`.
`ysiw'` wraps word in `'`.
`V + motion + S'` wraps selection in `'`.o

PS: Open wraps with space, close wraps without space.

** Commentary
`gcc` comments out a line.
`gc` comments target of a motion.

** VTR
`VtrOpenRunner` opens a new tmux pane attached to vim.
`VtrSendCommandToRunner` sends the command to runner i.e. `ruby sample.rb`
`VtrSendCommandToRunner` sends the command and opens a new attached tmux pane.
`VtrSendLinesToRunner` sends selected lines to runner.
`VtrAttachToPane` attaches Vim to a tmux pane.
