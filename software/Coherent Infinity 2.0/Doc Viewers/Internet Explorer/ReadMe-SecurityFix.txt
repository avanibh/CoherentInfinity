from http://www.microsoft.com/ie/security/download.htm


Download Area for Internet Explorer 3.0/3.01 Security Fix 
Effective March 13, 1997 

Known Issues 

    Windows NT Service Pack 1.0 or Below 
    If you are running Windows NT Service Pack 1.0 or below, a dialog box appears during installation of the fix (3.0b/3.01b)
    for either Internet Explorer 3.0 or 3.01. The dialog box states that it cannot copy a file to mshtml.dll. When this dialog
    box appears, do not choose to abort the installation. Instead, close Internet Explorer, and then click Retry in the dialog
    box. The fix will then be installed successfully. If you mistakenly choose to abort the installation, you should open the the
    System 32 directory and find the following two files: shdocvw.bad and mshtml.bad. Rename these files to shdocvw.dll and
    mshtml.dll. If you are running Windows NT Service Pack 2.0 or above, you are not affected by this problem. 