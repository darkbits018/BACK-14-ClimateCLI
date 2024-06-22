
# BACK-14 : ToDo CLI

**Instructions**
- clone the repository
- open current directory in terminal
- Install Requirments 
- Go to [openweathermap](https://openweathermap.org/api) and get your api key
- create .env file and add 
    ````
  openweathermap_api = "<your_api_key>"
  ````

**To make the command available globally, you need to add its directory to your system’s PATH.**
- Right-click on 'This PC' or 'Computer' on your desktop or in File Explorer.
- Click 'Properties'.
- Click 'Advanced system settings'.
- Click 'Environment Variables'.


- _**or you can just search Environment Variables**_


- In the 'System variables' section, find the Path variable and click 'Edit'.
- Click 'New' and add the path to the directory where taskmaster.bat is located. For example, C:\Users\YourName\Scripts.
- Click 'OK' to close all dialog boxes.
- You need to restart your command prompt to apply the changes to the PATH environment variable.

**Commands**
  ````
  climatecli <country/city>
  ````

_**without adding to path :**_
- open the directory in cmd
- and run
  ```
  python climatecli <country/city>
  ```