# FAQ
- Q: Will this work on a Old3DS?
- A: No. Snickerstream still relies on NTR CFW to work, so it doesn't work on o3DSes. They simply aren't powerful enough to stream their screens over wi-fi.

- Q: Will you make a Mac/Linux/<insert OS name here> port?
- A: No, AutoIt can only compile stuff on Windows. Even if you somehow find a way to compile it on other OSes, it uses Windows-specific functions internally. Even if you replace these functions, both Direct2D and GDI+ are Windows-specific libraries. In order to make a Windows port, Snickerstream would have to be completely rewritten in another language.
  
- Q: But then, can I run it using Wine?
- A: Yes! Even if I cannot ensure 100% compatibility for obivous reasons, Snickerstream should be as Wine-friendly as it gets. Wine added Direct2D support since version 1.8 and GDI+ has been supported for a long while now.

- Q: I've got issues with Virtual Console titles!
- A: That's not a bug related to Snickerstream - NTR's remoteplay function has many problems with Nintendo's official Virtual Console feature. I suggest you use homebrew emulators instead, many work very well both in terms of emulation and with NTR itself.

- Q: Will you add file uploading / CIA installing like kit-kat?
- A: No. Snickerstream has been built with a "by streamers, for streamers" philosophy which means anything that isn't related to streaming or that cannot improve it in any way will be considered extra bloat and isn't going to be implemented. Besides, there are already many better ways to upload files (FTP or Nintendo's own SMB) or install CIAs (FBI, both locally, via URL or even via QR), so they are completely unneeded.

- Q: What about remoteplay?
- A: I'm unsure as of now. You CAN already use any type of remoteplay programs togheter with Snickerstream (I suggest you go with Luma's integrated feature, it doesn't require you to install anything else and has many different clients that support it) but, on the other hand, could be handy. Right now the main focus is to give you the best streaming performance ever with the most features, but I guess I might think about it in later versions.

- Q: I've found a bug! What do I do?
- A: Read the troubleshooting section in the readme. If that doesn't help, set the loglevel to 3 and try to understand what's wrong. If that STILL doesn't help, check if it persists with other clients (mainly NTRViewer). If everything else fails, contact me and send me the log.

- Q: I've got a neat idea for a feature! Can I tell you about it?
- A: Sure, there have been already user-submitted features coded in so you're encouraged to do so! As long as it isn't outright impossible, it might make it in one of the next versions! :D