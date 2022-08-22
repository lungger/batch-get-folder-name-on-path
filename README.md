# batch-get-folder-name-on-path
this batch-script can get folder name from back to front on path

set Temp_path=%MAKEDIR%

**%MAKEDIR%** --what path you want to parsing<br><br>

for /l %%i in (1,1,**2**) do call :GetFolder --(x,x,**2**) third parameter meaning which folder want to get

ex: c:/test1/test2/test3/test4/test5 

**%folder%** = test4<br><br>



  
      
*If this is helpful to you, please don't be stingy to give stars*
