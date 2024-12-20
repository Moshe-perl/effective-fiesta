Project Description

This project focuses on managing file and directory permissions in Linux. It demonstrates how to modify permissions to align with an organization’s policies, ensuring proper access control.

Key Features
	1.	Understanding Permission Strings
	•	Permission strings (e.g., -rw-rw-rw-) are explained in detail, highlighting what each part represents for users, groups, and others.
	•	Examples include full directory access (drwxrwxrwx) and specific file permissions.
	2.	Modifying File Permissions
	•	Commands used to modify permissions are documented, such as removing write access for others.
	3.	Handling Hidden Files
	•	Hidden files are identified using ls -la.
	•	Permissions for hidden files are adjusted to restrict write access for everyone while allowing read access for the user and group.
	4.	Securing Directories
	•	Directory permissions are adjusted to ensure only the user can access specific directories.
	•	The execute permission for groups is removed for enhanced security.
Summary
	•	Permissions for others were modified to remove write access across files.
	•	Hidden files were secured with restricted write permissions and controlled read access.
	•	Directory access was limited to the user by removing execute permissions for the group.
