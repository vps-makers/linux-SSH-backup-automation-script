# linux-SSH-backup-automation-script
This script compresses the Linux `.ssh` directory, encrypts the backup with GPG, and securely transfers it to an external backup server. After a successful transfer, the local backup file is removed to prevent unauthorized access and protect sensitive SSH credentials.

# How to Use
This is a zip file; you should extract it on your Linux device or server. Then you need to make it executable with the `chmod` command, then edit the script with `nano` and add your destination server specifications to back up this file to another server.

# Read More
To learn how you can use this script and add it to cron schedule you can follow this article: 
https://vpsmakers.com/backup-ssh-key-ubuntu/
