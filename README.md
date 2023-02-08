# This code uses powershell to open a dialog box on Windows
# paste code into the Powershell ISE

#start

Add-Type -AssemblyName PresentationCore,PresentationFramework

[System.Windows.MessageBox]::Show('Turn me off')

#end
