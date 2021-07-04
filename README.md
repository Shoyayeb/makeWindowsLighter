# makeWindowsLighter
this is some files to make your windows faster and lighter by adding some system fixes and removing some pre loaded apps on windows 10
  
Run on Powershell(admin):

    Set-ExecutionPolicy Unrestricted -Scope CurrentUser
  
    ls -Recurse *.ps*1 | Unblock-File
	
    powercfg -duplicatescheme e9a42b02-d5df-448d-aa00-03f14749eb61
	  
    DISM.exe /Online /Cleanup-Image /Restorehealth
	  
    sfc /scannow
