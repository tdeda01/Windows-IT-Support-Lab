Wiindows IT Support and User Management Lab


PROJECT OVERVIEW

This hands-on lab simulates common IT Help Desk responsibilities using Windows 11 Home, including local user account manager, NTFS file permissions, and troubleshooting access issues.
Tools used include Windows 11 Home and Settings, file explorer, NTFS Security Settings and Windows Effective Access.


TASKS COMPLETED

Completed tasks were divided into folders, and supported with screenshots of the findings. 

A.User Account Management: A local standard user account, named ITLab_Alex was created, and verified that it had no administator privileges.

B.File and Folder Permissions: Created a practice directory at C:\IT-Lab\Shared-Documents. Read and Execute permissions were assigned to the test user, and later were tested by signing in with the test account.

C.Troubleshooting Unexpected Write Access: The user could modify a document despite being assigned Read permissions. Advanced Security Settings and Effective Access were used to investigate the user's permmissions, which revealed that the Authenticated Users group had inherited Modify permissions from the C: drive. To solve this, disabled inheritance was applied on the practice folder, then converted inherited permissions to explicit entries, and the Authenticated Users Modify entry was removed. This was verified by signing in as the test user again, and confirming that attempts to save changes to the original document were blocked.



SKILLS DEMONSTRATED: Windows User Account Management, NTFS File Permissions, Permission Inheritance, Troubleshooting and Root Cause Analysis, Access Control and Least Privilege, Technical Documentation. 













