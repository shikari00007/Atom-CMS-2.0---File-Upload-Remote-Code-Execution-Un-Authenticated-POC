# Atom-CMS-2.0---File-Upload-Remote-Code-Execution-Un-Authenticated-
Remote Code Execution (RCE)
* Exploit Author: Ashish Koli (Shikari)
* Vendor Homepage: https://thedigitalcraft.com/
* Software Link: https://github.com/thedigicraft/Atom.CMS
* Version: 2.0
* CVE: CVE-2022-25487
* About this:
* This script uploads webshell.php to the Atom CMS. An application will store that 
* file in uploads directory with unique number, which allows us to access Webshell.
* Usage : python3 exploit.py <IP> <Port> <atomcmspath>
* Example: python3 exploit.py 127.0.0.1 80 /atom
