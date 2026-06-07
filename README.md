this file is a messaging app with Python 
 neded= 
 Everything it uses comes included in Python, you don’t need to install anything:
ModulePurposeIncluded?tkinterGraphical interface PythonsocketNetwork chat PythonthreadingParallel threads PythonhashlibEncryption (SHA256) PythonstructBinary protocol PythonqueueMessage queue PythonurllibPublic IP PythonjsonParse IP PythonosFile management PythonwinsoundNotification sound Windows

To share it with someone you have two options:
Option A — Send them the .exe (easier, doesn’t need Python)
You compile with PyInstaller as before and send them the messenger95.exe from the dist folder.
Option B — Send them the .py (needs Python installed)
You send them the .py and they run it with:
python messenger95.py

To connect between two different PCs remember:

They have to be on the same WiFi network, or
Use the public IP with the port open on the router
Use the same key if they activate encryption
