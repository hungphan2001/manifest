<img src="https://raw.githubusercontent.com/CerberusOS/manifest/Pie/cerberus_banner.png">

CerberusOS
========

## Downloading Source
To initialize your local repository, use this command:

	repo init -u https://github.com/CerberusOS-Future/manifest.git -b Pie

Then to sync, use this command:

	repo sync -c -j8 --force-sync --no-clone-bundle --no-tags
	
	
	
## Building CerberusOS
After download CerberusOS source now you able to build rom by type
```
. build/envsetup.sh 
  lunch cerberus_CODENAME-userdebug
```
Then to start build
```
  mka cerberus
```
