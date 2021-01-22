This is a branch of kannibalox's version. It is a pretty big overhaul to make it work with Python 3 and Windows. While Python is cross-platform, the original PtpUploader has a lot of hardcoded Linux directories and stuff. I also simplified much of the installtion and requirements for the less tech-savy. There may be lots of issues with this, I've never used the original tool and I don't have a lot of stuff to test with so it's a work in progress.

With the PtpUploader's WebUI you can upload to PTP by specifying a torrent file and an IMDb or PTP link.
There is also an automatic mode built-in that can check announcements from IRC or RSS and upload everything automatically.

Supported sites for automatic mode:
* AlphaRatio
* Cinemageddon
* Cinematik
* DigitalHive
	* Thanks to CoFix!
* GFT
* HDBits
	* Thanks to cerbere!
* HD-Torrents
	* Thanks to Mako_1!
*  Karagarga
* TorrentBytes
* TorrentLeech
* FunFile
	* Thanks to dhosha!

SceneAccess support was removed on the 9th of July 2013 because of staff pressure...
RevolutionTT support was removed on the 15th of May 2015 because of staff pressure...

There is a helper [Greasemonkey script](https://raw.githubusercontent.com/TnS-hun/PtpUploader/master/PtpUploaderTorrentSender.user.js) available at to send torrents from a wide variety of sites directly to PtpUploader.

#### Questions, help

See [INSTALL.md](INSTALL.md) for installation instructions on Windows. Use kannibalox's install instructions if you aren't using Windows. You will need to make adjustments to the instructions but if you're using Linux you should be able to figure it out. 