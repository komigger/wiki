# Extracting a Plesk Backup File

## Where to Download Your Account Backup

If the HelioHost team made a backup of your hosting account data, you can retrieve it by visiting [https://heliohost.org/backup](https://heliohost.org/backup/) and following the instructions on the page to download the file.

Inside the downloaded backup file, there will be a large file named `backup_user-data_##########.tzst` which contains all your files.  

The file will be in a format called `Z-standard` and will need to be extracted.

## How to Extract Your Account Data from the Backup File

### Download and Install 7-Zip with Zstandard Support

Download and install the version of 7-Zip which supports Zstandard here: [https://github.com/mcmilk/7-Zip-zstd](https://github.com/mcmilk/7-Zip-zstd/releases)

### Access Your Files

* Navigate to the main backup file named `pleskbackup-YourAccountUsername.tar`
* Extract the `.tar` file with the version of 7-Zip you just installed
* The files will be extracted to a folder named `pleskbackup-YourAccountUsername`
* Open the folder and navigate to the `domains` folder
* Open the next folder, named `YourAccountUsername.heliohost.us` or `YourAccountUsername.helioho.st`
* Navigate to the file named `backup_user-data_##########.tzst` 
* Open the file to access your data

### Screenshot Example

![](../../.gitbook/assets/extract-plesk-backup-file.png)

### Further Support

If after following the above steps, you are unable to download or extract your backup data, please post a topic in the [Customer Support forum](https://helionet.org/index/forum/45-customer-service/?do=add) and make sure you provide details of the problem, including what steps you have tried, and any error messages encountered.

## References

The original discussion which prompted the creation of this tutorial for extracting Plesk backup files can be found [here](https://helionet.org/index/topic/58777-solved-suspended-account/#comment-260423).
