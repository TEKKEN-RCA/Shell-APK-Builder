# Description
The Shell APK Builder is a shell script project for Build Android Application.

# Warning
The Shell APK Builder project need be on Internal Storage Directory
/data/data/com.android.application is a Internal Storage Directory of a Android Application.

# Command
//Declares FILES_DIR environment variable.
FILES_DIR=/data/data/com.android.application/files

//Declares RUN_SHELL_PATH environment variable.
RUN_SHELL_PATH=$FILES_DIR/Shell-APK-Builder/shell/run.sh

//Executes run.sh shell script.
$RUN_SHELL_PATH
