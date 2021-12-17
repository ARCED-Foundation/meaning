# meaning

A Stata module that uses internet to search for the meaning for a word or phrase, and print in a temporary text file. You can listen to the pronunciation using pronounce option.

The command works in windows only. It searches meaning for a word or phrase, and paste the search result in a temporary notepad file. If you close the notepad window, the search result is deleted. If you specify pronunciation option, make sure the audio from your computer is on.

This program uses windows powershell and internet exploer to search in google.


# Installation

```Stata
** Install from ssc
    ssc install meaning

** Install from GitHub
    net install meaning, all replace from(https://raw.githubusercontent.com/ARCED-Foundation/meaning/master)

```
## Syntax
```stata
meaning [, options]

help meaning
```

## Options
| Options      | Description |
| ---        |    ----   |
| <u>pro</u>nounce |  The name of the XLSform, including the path | 

## Example Syntax
```Stata
meaning poverty
meaning poverty, pronunciation
meaning poverty, pro
```

Please report all bugs/feature request to the <a href="https://github.com/ARCED-Foundation/meaning/issues" target="_blank"> github issues page</a>.

## Author
Mehrab Ali <br>
Email: mehrabbabu@gmail.com