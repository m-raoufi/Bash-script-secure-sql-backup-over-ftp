# Bash-script-secure-sql-backup-over-ftp
Create an encrypted backup file of your MySQL database and transfer it to a FTP server

Usage:

Step 1
Downlaod this bash file (script.sh) and copy to your server for example: /usr/home

Step 2
Edit server information in bash file
  For example:
    DATABASE_NAME="example_db"
    DATABASE_USERNAME="root"
    DATABASE_PASSWORD="root"

Step 3
Complete your ftp server information in bash file
  For example:
    FTP_ADDRESS="your ftp address"
    FTP_USERNAME="your ftp username"
    FTP_PASSWORD="your ftp password"

Step 4
Don't forget to fill your FILE_PASSWORD= (you will need this to decrypt your backup file)

Step 5
Grant execution permission to the bash file
    chmod +x /use/home/script.sh

Step 6
Run the script
  ./script.sh
