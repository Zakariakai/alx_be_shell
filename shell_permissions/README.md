The first script, 0-switch_user, is supposed to switch the current user to "betty" with a command containing exactly 8 characters. Opening a text editor, create a new file and then add the necessary script content—save a command to switch users using `su betty`. Save and close the file, then make the file executable by changing into the directory where the script is parked and running the appropriate command. Subsequent runs of the script will change the user to "betty" through the `su betty` command.

The second script, `1-who_am_i`, prints the effective current username. You open a text editor, create a new file, and paste the script that simply uses the command `whoami`. You save, make the script executable, and then run it. The username appears on screen.

The third script, `2-create_hello`, creates an empty file called hello in the current working directory. You open the text editor and write the command, save, give permission to execute, and then run it—and voilà, you have the empty file created.

The fourth script, `3-add_execute_permission`, adds execute permission to the owner for the file "hello": You do the same procedure, create the script, save it, make it executable, and execute it to modify the permissions.

In the fifth script, `4-set_permissions`, you are setting particular permissions on the "hello" file: the owner and group have execute permission, and others have read permission. Once this script is created and run, appropriate permissions have been set.

The sixth script, `5-set_mode`, sets the mode for the "hello" file to `-rwxr-x-wx`, so that the owner has full permissions, the group has read and execute permissions, and others have execute permissions. Like the rest, you create, save, and run this script to get the intended permission configuration.

Upon execution of these scripts, one must account for the results through the execution of basic file-management commands to test permissions and access the "hello" file. This script shall conduct some of the most basic file management and user switching in the Linux environment; it shows how one can maintain good user access manipulation and manage file permissions with the use of Bash scripting, including user switching through `su betty`.
