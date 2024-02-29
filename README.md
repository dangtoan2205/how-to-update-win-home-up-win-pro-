# how-to-update-win-home-up-win-pro-

Step 1: Run CMD in administrator.

Copy code: 

sc config LicenseManager start= auto & net start LicenseManager
sc config wuauserv start= auto & net start wuauserv
changepk.exe /productkey VK7JG-NPHTM-C97JM-9MPGT-3V66T
exit
exit


Step 2: Right click paste to CMD. wait update. ( Không cần chú ý mã lỗi 0x80070490)

Step 3: Restart the computer to complete the update to Windows 11 Pro and data.
