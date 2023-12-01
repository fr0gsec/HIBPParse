# HIBPParse 

This is a simple PowerShell 1-liner to parse data breach json files from Have I Been Pwned. In order to get these files you have to have your domain registered under their website for a fee. Just download the Json, name it pwned.json. There shouldn't be any @'s or domains in the json format but if there is you may need to parse that out first. There is a VIP section that you can edit to include your list of special users that you would want to be notified of immediately (C-suite, presidents, infosec professionals) if they were breached.

Example using the Chess data breach:

When prompted for the name of the breach, enter "Chess"

Edit $vipList = 'vip1', 'vip2'` to be $vipList = 'ciso', 'president'

Then copy the 1-liner and run it, or run the .ps1. 

PS C:\Users\nimble\Desktop> . .\hibpparse.ps1
The script found 8 names in the JSON file that match 'Chess'. The names have been written to 'pwned.txt'. There are no VIPs in this list.
