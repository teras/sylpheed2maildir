# sylpheed2maildir
A script to automatically convert a sylpheed mailbox into maildir format

This simple bash script is able to convert a sylpheed mail box directory to maildir format. It is also able to properly handle nested directories of KMail, making it easy to migrate from Sylpheed to KMail.
To run it simply execute it with argument the directory of the old mailbox (e.g. "Mail.sylpheed") and an optional argument of the destination directory ( e.g. "Mail" )

Notices:
- It is recommended to rename "Mail" directory so something like "Mail.sylpheed" before starting the program, in case something goes wrong.
- The script should be in the $PATH in order to recursively scan all directories.
