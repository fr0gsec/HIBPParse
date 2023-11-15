# HIBPParse 

This is a simple PowerShell 1-liner to parse data breach json files from Have I Been Pwned. In order to get these files you have to have your domain registered under their website for a fee. Just download the Json, name it pwned.json. Edit the powershell script variable at the beginning to reference the data breach of your choosing, then run the 1-liner in the same directory. There is a VIP section that you can edit to include your list of special users that you would want to be notified of immediately (C-suite, presidents, infosec professionals) if they were breached.
