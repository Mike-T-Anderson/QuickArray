# QuickArray
A PowerShell function that is used to create a quick and dirty array from a paste of text. It takes data separated by line breaks, and outputs an array, containing one index per line.

## Why?
While not very usefull for a script, if you're working in a prompt and are given some raw data that you need to run a command on, this makes it simple to get that data into your prompt, without the need to save the data into a file and use `Get-Content` to import the data, or use the `@()` array syntax inline.

## Installation
Via the PowerShell Gallery on PowerShell 5.0 and up (Recommended):
```Powershell
PS> Install-Module QuickArray
```

Via Git:
1. Change directory into one of your $env:psmodulepath directories.
2. Run the following:
```Powershell
PS> git clone https://github.com/MaxAnderson95/QuickArray.git
```

Manually:
1. Download a zip'd copy of the repo https://github.com/MaxAnderson95/QuickArray/archive/master.zip
2. Unzip the repo into one of your $env:psmodulepath directories.

## Usage
Simply run the `New-QuickArray` Cmdlet and output the data into a variable, or use it inline within a parenthetical (see example)

![gif showing how to use inline in a command](https://i.imgur.com/vbCGTv6.gif)
