$ErrorActionPreference = 'silentlycontinue'
$DriveNumber = Read-Host - Prompt 'Input Drive/File Path Desired'
$File_name = Read-Host -Prompt 'Input file  name'
Get-ChildItem "$DriveNumber" -Filter "$File_name" -Recurse

function Show-Menu
{
    parm (
        [string]$Title = 'Menu Options'
    )
    cls
    Write-Host "===============$Title================="

    Write-Host "1: Press '1' for Option 1"
    Write-Host "2: Press '2' for Option 2"
    Write-Host "3: Press '3' for Option 3"
    Write-Host "Q: Press 'Q' to quit."
}

do
{ 
    Show-Menu
    $input = Read-Host "Please select an option!!! Damn it!!!"
    switch ($input)
    {
        '1'{
            cls
            'You picked option 1'
        }
        '2'{
            cls
            'You picked option 2'
        }
        '3'{
            cls
            'You picked option 3'
        }
        'q'{
            return
        }

    }
    
    pause
}
until ($input -eq 'q')
