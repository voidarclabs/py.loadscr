# Python loading screen prompt generator

This python file will pick a random line from `msg.txt` and print it to the screen.
If requested multiple prompts, it will print one every interval.

### To call the function
```
import load
load.msg(<number of prompts>, <interval>)
```

Please note that:
* It will not clear the screen after every prompt
* It will put each prompt on a new line
