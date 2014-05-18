alsi
====

A command-line system information tool for Arch Linux.

```
usage: alsi [options]

main options:
    -a  --archey         : use archey's logo
    -n  --screenfetch    : use screenfetch's logo
    -f  --file-logo=file : read logo from a specific file
    -t  --text-color     : use color for values as well
    -l  --list           : output the lines bellow the logo
    -u  --usage-colors   : highlight the usage for RAM and HDD
        --usage-bcolors  : same as above, but with bold colors

    --bold=[color]       : change the bold color
    --normal=[color]     : change the normal color
    --[color]            : set color1 and color2 at the same color.

    Available colors are: black, red, green yellow,
                          blue, purple, cyan and white
other options:
    -s --screenshot     : take a screenshot
       --update-config  : update the configuration file
       --noconfig       : don't load the configuration file
```
