# grabtcp
## A TCP banner grabber script

This is a simple shell scrip to bannergrab tcp ports.

### Requirements:
ncat
bash

#### USAGE:
```sh

           ________            ___.    __                 
	 /  _____/___________ \_ |___/  |_  ____ ______  
	/   \  __\_  __ \__  \ | __ \   __\/ ___\\____ \ 
	\    \_\  \  | \// __ \| \_\ \  | \  \___|  |_> >
	 \______  /__|  (____  /___  /__|  \___  >   __/ 
	        \/           \/    \/          \/|__|    
		     Grabtcp!
		A tcp banner grabber.
Usage:
bannergrabber [HOST] [PORT] [VERBOSITY] [REPEAT]
-h, --help	show this help menu

Required: HOST & PORT
Optional: REPEAT & VERBOSITY
EX: bannergrabber 192.168.1.1 8080 -vvv 3
```
