# emacs-pomodoro-timer
TODO build this...

## How it will work

Elisp function `run-at_time` can be used to execute a function at a later point in time.

`(run-at-time "20:30" nil #'kill-emacs)`

If the function you want to call takes parameters, you can specify them as additional parameters to run-at-time:

`(run-at-time "5 sec" nil #'message "Tempus volat, hora fugit.")`

So it should be possible to create a mode that does things at time intervals like changing to another buffer.
