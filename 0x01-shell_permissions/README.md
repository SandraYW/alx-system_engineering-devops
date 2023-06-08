This is the directory for shell permissions

Shell Permissions Script Report

This report provides an overview of the scripts created to fulfill the tasks related to shell permissions.

Task 0: My name is Betty
Script: 0-iam_betty
Description: This script switches the current user to the user betty.

Task 1: Who am I
Script: 1-who_am_i
Description: This script prints the effective username of the current user.

Task 2: Groups
Script: 2-groups
Description: This script prints all the groups the current user is part of.

Task 3: New owner
Script: 3-new_owner
Description: This script changes the owner of the file hello to the user betty.

Task 4: Empty!
Script: 4-empty
Description: This script creates an empty file called hello.

Task 5: Execute
Script: 5-execute
Description: This script adds execute permission to the owner of the file hello.

Task 6: Multiple permissions
Script: 6-multiple_permissions
Description: This script adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.

Task 7: Everybody!
Script: 7-everybody
Description: This script adds execution permission to the owner, the group owner, and other users, to the file hello.

Task 8: James Bond
Script: 8-James_Bond
Description: This script sets the permission to the file hello as follows: owner has no permission, group has no permission, and other users have all permissions.

Task 9: John Doe
Script: 9-John_Doe
Description: This script sets the mode of the file hello to -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello.

Task 10: Look in the mirror
Script: 10-mirror_permissions
Description: This script sets the mode of the file hello the same as the mode of olleh.

Task 11: Directories
Script: 11-directories_permissions
Description: This script adds execute permission to all subdirectories of the current directory for the owner, the group owner, and all other users.

Task 12: More directories
Script: 12-directory_permissions
Description: This script creates a directory called my_dir with permissions 751 in the working directory.

Task 13: Change group
Script: 13-change_group
Description: This script changes the group owner to school for the file hello.
