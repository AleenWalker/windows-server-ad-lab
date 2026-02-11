Set-ADAccountPassword -Identity $args[0] -Reset `
-NewPassword (ConvertTo-SecureString "TempP@ss123" -AsPlainText -Force)
