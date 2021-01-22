Installation
==================

A lot of effort was made to simplify the installation. Right now, that has king of made it a bit bloated but I hope to reduce that.

1. Install Python (I'm not helping with that)
2. Clone or download the repo.
3. Install the requirements in requirements.txt. You can do this by navigating to the requirements.txt directory in the command line and run 'pip install -r requirements.txt'.
4. Rename settings.ini.example to settings.ini and make any changes needed. At minimum, you need to add your PTP info.

That should be it. In the future, I might simpliy this more. See the "Starting PtpUploader" section for how to start it.

Configure Torrent Client
==================
Look at kannibalox's version for information on that (https://github.com/kannibalox/PtpUploader/blob/develop/INSTALL.md). I've only been able to test this up to a certain point of compatibility for Python 3 and Windows. I haven't had anything to upload to test further so it might not work. If it doesn't contact me and I will try my best to fix it.

Starting PtpUploader
====================

Navigate to the PtpUploader directory in the command prompt and rain main.py.

1. python.exe main.py