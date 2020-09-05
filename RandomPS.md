Random PS commands notes in no particular order

The following command is the equivalent of SET in dos
    ls env:\

Shows currently loaded PSsnapin 
    Get-PSSnapin

List all available Modules
    Get-Module -ListAvailable | more


default location where PS loads modules from
    $env:psmodulepath
    $env:psmodulepath -split ";"

Find-Module
Get-PSRepository

test change