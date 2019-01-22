# Importing files to Sauce Labs
An example of how to import files to a VM on Sauce Labs.  This uses the prerun capability to pull the files. 

# Usage
Use the proper executable to pull for your VM. For example, Windows use:
```
'prerun':{
  'executable': 'https://raw.githubusercontent.com/phillsauce/saucelabs-import-files/master/WinDownloadFiles.bat',
},
```
