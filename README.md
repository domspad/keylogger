# keylogger
an daemon app that will log all keystrokes while running e.g. (running `python keylogger.py` in a terminal session -- though ideally this script can be set to run whenever the computer is awake)

## Specifications brainstorm

- runs in the background (daemon process)
- format of keystroke logging : 
each stroke has its own line of the form
`<timestamp> <key>`
though not sure how difficult that will be
- automatically begins running when the computer is awake

## Potential uses

- this is mainly because I'm curious what it would take to do this in Python :) Also to learn a bit more about operating systems
- what is the distribution of keystrokes?
- can the next keystroke be predicted based on the past 'N'?
- what can we infer about the users behavior just from this data? (i.e. are they coding? Writing a letter?...)

