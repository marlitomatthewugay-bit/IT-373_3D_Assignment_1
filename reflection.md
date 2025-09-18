In terms of setting up the virtual environment, there were no problems, and I was able to create one fairly quickly. 
Installing Django, however, had a bit of complications as when I initially tried to install Django, a pop-up from VScode showed and stated that if I have a global version of Django and I try to install Django through the virtual environment, it will have complications. 
So I clicked on it, then remembered I don’t have a global version of Django and cancelled the process, which promptly cancelled the installation. 
The environment determined that Django has been downloaded when I try to install it again, but when I try to call the Django version, an error occurred. 
So, I deleted the virtual environment and redid the installation process.
After that, I followed the steps to create the server, creating the “core” file, the templates, and the HTML files. 
It went smoothly, but when it was time to save and see the display, the site said that there was no file to call. 
So I tried debugging files and see if there are any mistakes I made, until I checked settings.py and realized I forgot to write ‘core’ onto “INSTALLED APPS = []”. 
After that, everything went well, and the website was running.
