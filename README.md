# BulkTFTP
CUCM Bulk TFTP Upload
This program will traverse a local directory recursively and upload 
all files while maintaining the directory structure.
You can pass in the parameters on the command line or edit the
sys.argv line at the bottom of the script.

Install Python 2.7 and choose the option to add to path (off by default)
Then install two modules
C:\>pip install requests
C:\>pip install BeautifulSoup
May need to use "python -m pip install requests"

Then run the program CUCM-Bulk-TFTP-Upload.py
C:\>python tftp.py hostname/IP username password localdirectory

Windows formatting for local directory- C:\\TFTP-Root\\tftpfiles
