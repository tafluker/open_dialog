# open_dialog box for windows in powershell
# paste code into the Powershell ISE

#start
Add-Type -AssemblyName PresentationCore,PresentationFramework
[System.Windows.MessageBox]::Show('Turn me off')
#end
