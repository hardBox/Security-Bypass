# Security-Bypass
PoC for Little Flocker window bypass (same concept also working on Little Snitch, BlockBlock etc).

Description: This PoC run an external program and detect when Little Flocker window appear then it automatically click on the "Allow" button by calculating the distance (so it works pretty well on every resolution). The LF window only appear for a fraction of second.

Usage: ./Security-Bypass-Binary [command] [args...]

Example: ./Security-Bypass-Binary /bin/cat /Users/Sabri/Desktop/topsecret.txt

**This PoC has been made for Little Flocker but with minor modifications it can also works with Little Snitch** *(Even with GUI scripting disabled)***, BlockBlock and many more!**

**Vulnerable version of Little Flocker: <= 1.3.0 (latest)**

**Vulnerable version of Little Snitch: <= 3.7.1 (latest)**

**Vulnerable version of BlockBlock: <= 0.9.4 (latest)**

![https://github.com/pwnsdx/Security-Bypass/raw/master/demo.gif](https://github.com/pwnsdx/Security-Bypass/raw/master/demo.gif)
