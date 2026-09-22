# Shell, permissions

This directory contains bash scripts for learning Linux permissions and useridentity management.

* `0-iam_betty`: Switches the current user to the user `betty`.
* `1-who_am_i`: Prints the effective username of the current user.
* `2-groups`: Prints all the groups the current user is part of.
* `3-new_owner`: Changes the owner of the file `hello` to the user `betty`.
* `4-empty`: Creates an empty file called `hello`.
* `5-execute`: Adds execute permission to the owner of the file `hello`.
* `6-multiple_permissions`: Adds execute permission to the owner and group owner, and read permission to other users, for the file `hello`.
* `7-everybody`: Adds execution permission to the owner, group owner, and other users for the file `hello`.
* `8-James_Bond`: Sets the permissions of the file `hello` to no permissions for owner and group, and full permissions (`rwx`) for other users (`007`).
* `9-John_Doe`: Sets the mode of the file `hello` to `-rwxr-x-wx` (`753`).
* `10-mirror_permissions`: Sets the permission mode of the file `hello` to match the permission mode of the file `olleh`.
* `11-directories_permissions`: Adds execute permission to all subdirectories of the current directory for owner, group, and others without altering regular files.
